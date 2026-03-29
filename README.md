# AFM Moda Oceánica - Landing Page

> Proyecto realizado como entrega del **PROYECTO: LANDING PAGE** del módulo 3 "Web Design [Fundamentals]" del máster **Rock{TheCode}** de ThePower / Hackio.

## Demo

[Ver la landing page en vivo](https://proyecto-landing-page-1.vercel.app/)

## Descripción

Landing page de una marca ficticia de moda sostenible inspirada en el océano. La web presenta una colección de productos (sudaderas, camisas, camisetas y suéteres) elaborados con algodón ecológico en talleres españoles.

> **Nota:** Este proyecto es un ejercicio académico. No es una tienda real. Las imágenes y vídeos han sido generados con herramientas de Inteligencia Artificial.

## Arquitectura del proyecto

```
Proyecto-LANDING-PAGE-1/
├── index.html              # Página principal (HTML5 semántico)
├── styles/
│   └── desktop.css         # Estilos CSS con variables, Grid, Flexbox y responsive
├── assets/
│   ├── logo.webp           # Logo de la marca (también usado como favicon)
│   ├── hero1.mp4           # Vídeo de fondo del hero
│   ├── hero1c.mp4          # Vídeo alternativo del hero
│   ├── imagen1.webp        # Producto: Sudaderas
│   ├── imagen2b.webp       # Producto: Camisas Oxford
│   ├── imagen3b.webp       # Producto: Camisetas
│   ├── imagen4.webp        # Producto: Suéteres
│   ├── instagramwhite.svg  # Icono Instagram
│   ├── x.svg               # Icono X (Twitter)
│   ├── tiktok.svg          # Icono TikTok
│   ├── youtube.svg         # Icono YouTube
│   └── linkedin.svg        # Icono LinkedIn
└── README.md
```

## Secciones de la web

| Sección | Descripción |
|---------|-------------|
| **Header** | Navegación fija con logo y menú responsive con Flexbox |
| **Hero** | Vídeo de fondo a pantalla completa con título y botón CTA |
| **Productos** | Grid de 4 productos con enlaces reales a Amazon |
| **Sobre nosotros** | Filosofía de la marca con fondo azul marino |
| **Newsletter** | Formulario de suscripción por email |
| **Footer** | Redes sociales, copyright y disclaimer |

## Tecnologías y técnicas utilizadas

- **HTML5 semántico**: `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`
- **Etiquetas multimedia**: `<video>`, `<source>`, `<img>`
- **Formularios HTML5**: `<form>`, `<input type="email">`, `<button>`, `<label>`
- **Meta etiquetas SEO**: `description`, `keywords`, `author`
- **CSS3 con variables**: colores, espaciado, tipografía, bordes y sombras definidos en `:root`
- **CSS Grid**: layout de productos (4 columnas en desktop, 2 en tablet, 1 en móvil)
- **Flexbox**: navegación, formulario de newsletter e iconos de redes sociales
- **Position**: `fixed` para el header, `relative` y `absolute` para el hero con vídeo
- **Web Responsive**: 2 media queries (tablet a 768px y móvil a 480px)
- **Reutilización de estilos**: clase `.btn` compartida en hero, productos y formulario

## Requisitos cumplidos

- [x] Buen uso de variables CSS
- [x] Reutilización de estilos con clases (`.btn`, variables compartidas)
- [x] Uso de Grid y Flex
- [x] Página full responsive
- [x] Ningún error en el HTML
- [x] Buena semántica y accesibilidad
- [x] Meta etiquetas para SEO
- [x] Enlaces a productos reales (Amazon)

## Despliegue

El proyecto se despliega automáticamente en **Vercel** con cada push a la rama `main`.

## Autora

**Araceli Fradejas Muñoz**
- [LinkedIn](https://www.linkedin.com/in/araceli-fradejas-munoz-transformaciondigital/)
- [Instagram](https://www.instagram.com/goldilocks1013x/)
- [X (Twitter)](https://x.com/AraceliFradejas)
- [TikTok](https://www.tiktok.com/@arucci1)
- [YouTube](https://www.youtube.com/@aracelifradejasmunoz2758)

---

# AFM Ocean Fashion - Landing Page (English)

> Project submitted as the **LANDING PAGE PROJECT** for Module 3 "Web Design [Fundamentals]" of the **Rock{TheCode}** master program at ThePower / Hackio.

## Demo

[View the live landing page](https://proyecto-landing-page-1.vercel.app/)

## Description

Landing page for a fictional sustainable fashion brand inspired by the ocean. The website showcases a product collection (sweatshirts, shirts, t-shirts, and sweaters) made with organic cotton in Spanish workshops.

> **Note:** This is an academic project. It is not a real store. Images and videos were generated using Artificial Intelligence tools.

## Project Architecture

```
Proyecto-LANDING-PAGE-1/
├── index.html              # Main page (semantic HTML5)
├── styles/
│   └── desktop.css         # CSS styles with variables, Grid, Flexbox & responsive
├── assets/
│   ├── logo.webp           # Brand logo (also used as favicon)
│   ├── hero1.mp4           # Hero background video
│   ├── hero1c.mp4          # Alternative hero video
│   ├── imagen1.webp        # Product: Sweatshirts
│   ├── imagen2b.webp       # Product: Oxford Shirts
│   ├── imagen3b.webp       # Product: T-Shirts
│   ├── imagen4.webp        # Product: Sweaters
│   ├── instagramwhite.svg  # Instagram icon
│   ├── x.svg               # X (Twitter) icon
│   ├── tiktok.svg          # TikTok icon
│   ├── youtube.svg         # YouTube icon
│   └── linkedin.svg        # LinkedIn icon
└── README.md
```

## Website Sections

| Section | Description |
|---------|-------------|
| **Header** | Fixed navigation with logo and responsive Flexbox menu |
| **Hero** | Full-screen background video with title and CTA button |
| **Products** | 4-product grid with real links to Amazon |
| **About Us** | Brand philosophy with navy blue background |
| **Newsletter** | Email subscription form |
| **Footer** | Social media links, copyright, and disclaimer |

## Technologies and Techniques

- **Semantic HTML5**: `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`
- **Multimedia tags**: `<video>`, `<source>`, `<img>`
- **HTML5 Forms**: `<form>`, `<input type="email">`, `<button>`, `<label>`
- **SEO meta tags**: `description`, `keywords`, `author`
- **CSS3 with custom properties**: colors, spacing, typography, borders, and shadows defined in `:root`
- **CSS Grid**: product layout (4 columns on desktop, 2 on tablet, 1 on mobile)
- **Flexbox**: navigation, newsletter form, and social media icons
- **Position**: `fixed` for the header, `relative` and `absolute` for the video hero
- **Responsive Design**: 2 media queries (tablet at 768px and mobile at 480px)
- **Style reuse**: `.btn` class shared across hero, products, and form

## Requirements Met

- [x] Good use of CSS variables
- [x] Style reuse through classes (`.btn`, shared variables)
- [x] Use of Grid and Flex
- [x] Full responsive page
- [x] No HTML errors
- [x] Good semantics and accessibility
- [x] SEO meta tags
- [x] Links to real products (Amazon)

## Deployment

The project is automatically deployed on **Vercel** with every push to the `main` branch.

## Author

**Araceli Fradejas Muñoz**
- [LinkedIn](https://www.linkedin.com/in/araceli-fradejas-munoz-transformaciondigital/)
- [Instagram](https://www.instagram.com/goldilocks1013x/)
- [X (Twitter)](https://x.com/AraceliFradejas)
- [TikTok](https://www.tiktok.com/@arucci1)
- [YouTube](https://www.youtube.com/@aracelifradejasmunoz2758)
