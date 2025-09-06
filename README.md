# Tripleten web_project_homeland

# De patria a patria — Sprint 5 (TripleTen)

Galería responsive con historias e imágenes de las ciudades natales del equipo de TripleTen. Implementa maquetación semántica, metodología BEM (estructura plana) y estilos adaptativos para 320–768–1280 px.

## 🚀 Demo

**GitHub Pages:** https://carlo-spada.github.io/web_project_homeland/

## 📐 Diseño y breakpoints

- Puntos de ruptura: **544 px** y **1024 px** (intervalos: 320–544, 544–1024, ≥1024).
- Ancho máximo de la página: **1280 px**.
- Tipografía: **Inter** (fuentes locales).

## 🧱 Tecnologías y técnicas

- **HTML5 semántico**
- **CSS (BEM Flat)**: `blocks/*.css` (un archivo por bloque)
- **Normalize.css** (vendor)
- **Fuentes locales** (`vendor/fonts/Inter-4/web/*.woff2`) + `fonts.css`
- **CSS Variables** (`:root`), **clamp()**, **min()**, **max()**
- **Flex/Grid** donde aplica
- **Media queries** a 34em (544 px) y 64em (1024 px)
- **object-fit**, reglas globales para medios fluidos
- Suavizado de fuentes y `text-rendering: optimizeLegibility`
- Preferencias de accesibilidad: `prefers-reduced-motion`

## 🗂 Estructura del proyecto

```
web_project_homeland/
├── blocks/
│ ├── globals.css
│ ├── page.css
│ ├── header.css
│ ├── lead.css
│ ├── intro.css
│ └── footer.css
├── images/
│ ├── logo.svg
│ └── lead-hero.jpg
├── pages/
│ └── index.css # solo @import de CSS
├── vendor/
│ ├── normalize.css
│ ├── fonts.css
│ └── fonts/
│ └── Inter-4/
│ └── web/\*.woff2
├── favicon.ico
└── index.html
```
