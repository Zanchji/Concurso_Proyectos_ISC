# XX Concurso de Proyectos de Innovación - ISC TSJ Zapopan

Sitio web oficial refactorizado y optimizado para el Concurso de Proyectos de Innovación de la Academia de Ingeniería en Sistemas Computacionales.

##  Sitio Publicado en Producción
- **URL del Proyecto:** [https://zanchji.github.io/Concurso_Proyectos_ISC/](https://zanchji.github.io/Concurso_Proyectos_ISC/)

##  Resumen de Mejoras Técnicas Implementadas

### 1. Estructura y Semántica Web (HTML5)
- **Eliminación de contenedores genéricos:** Se sustituyeron las etiquetas `<div>` por elementos semánticos (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<time>`).
- **SEO y Metadatos Open Graph:** Inclusión de etiquetas SEO clave (`description`, `keywords`, `author`) y Open Graph (`og:title`, `og:description`, `og:image`) para previsualizaciones en redes sociales y mensajería.
- **Accesibilidad (a11y):** Implementación de atributos `aria-*`, etiquetas `alt` en imágenes y contraste accesible.

### 2. Diseño, Maquetación y UX (CSS3)
- **Enfoque Mobile-First:** Maquetación responsiva adaptable desde 320px+ mediante CSS Grid y Bootstrap 5.
- **Variables CSS:** Uso de variables cromáticas (`--primary`, `--accent`, `--secondary`) alineadas a la identidad institucional de TecMM.
- **Modo Oscuro con Alto Contraste:** Selector opcional con persistencia en `localStorage` ajustado para ofrecer legibilidad óptima.

### 3. Dinamismo e Interactividad (JavaScript ES6+)
- **Contador Regresivo:** Reloj en tiempo real que calcula días, horas, minutos y segundos restantes para el evento.
- **Validación Interactiva:** Validación del correo institucional (`@isc.edu.mx` / `@zapopan.tecmm.edu.mx`) en tiempo real con alertas dinámicas.
- **Catálogo Filtrable:** Filtro de proyectos por áreas temáticas mediante manipulación del DOM.

### 4. Rendimiento y Buenas Prácticas
- **Carga Perezosa:** Atributo `loading="lazy"` integrado en las imágenes de la plataforma.
- Auditoría optimizada en Google Lighthouse alcanzando puntuaciones superiores a 85 en rendimiento y accesibilidad.

## 🛠️Tecnologías Utilizadas
- HTML5 Semántico
- CSS3 & Bootstrap 5.3
- JavaScript ES6+
- FontAwesome Icons & Google Fonts
- GitHub Pages & GitHub Desktop