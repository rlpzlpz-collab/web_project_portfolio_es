# Portafolio — Ricardo López

Sitio web de portafolio personal, desarrollado con HTML y CSS puro (sin frameworks). Presenta información profesional, habilidades técnicas, proyectos destacados y datos de contacto.

## 🚀 Demo

Publicado con GitHub Pages: https://rlpzlpz-collab.github.io/web_project_portfolio_es/

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3 (Flexbox, CSS Grid, `linear-gradient`, `aspect-ratio`)
- Fuentes personalizadas (`@font-face`): Archivo Black y Open Sans
- Diseño responsivo con múltiples breakpoints (ver abajo)

## ✨ Características

- Header con foto de perfil, presentación y links de contacto
- Sección de habilidades y herramientas con íconos
- Tarjetas de proyectos destacados, cada una con:
  - Imagen de vista previa con degradado inferior (overlay) para que los badges de tecnología resalten sobre cualquier imagen
  - Badges de tecnologías usadas
  - Descripción del proyecto y logros
  - Links a demo en vivo y repositorio
- Footer de contacto con enlaces a redes sociales

## 📱 Diseño responsivo

El sitio está maquetado con un enfoque _desktop-first_ y usa los siguientes puntos de ruptura:

| Breakpoint             | Rango aproximado       | Cambios principales                                                                                                                                   |
| ---------------------- | ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Base (sin media query) | ≥ 1023px, hasta 1440px | Diseño de escritorio: imagen de perfil flotante junto al título, tarjetas de proyecto en 2 columnas                                                   |
| `max-width: 1023px`    | 768px – 1023px         | Imagen de perfil reducida, título/subtítulo con ancho fluido para no encimarse con la imagen, tarjetas de proyecto en 1 columna con altura automática |
| `max-width: 767px`     | < 767px                | Imagen de perfil a ancho completo arriba del texto, links de contacto apilados en columna, íconos de herramientas en filas con wrap                   |

## 📁 Estructura del proyecto

```
├── index.html
├── styles/
│   ├── normalize.css
│   └── index.css
├── fonts/
├── images/
│   ├── social-media/
│   └── ...
└── README.md
```

## 💻 Cómo verlo localmente

1. Clona el repositorio:
   ```
   git clone https://github.com/rlpzlpz-collab/web_project_portfolio_es.git
   ```
2. Abre `index.html` en tu navegador (no requiere instalación ni servidor).

## 📬 Contacto

- Email: r.lpz.lpz@gmail.com
- LinkedIn / Facebook / Instagram / X: enlaces disponibles en el footer del sitio
