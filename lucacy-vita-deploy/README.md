# Lucacy Vita

Landing page de **Lucacy Vita** — Suplementos & Vitaminas naturales.

📍 723 Jersey Ave, Elizabeth, NJ
📱 +1 (908) 414-5276
✉️ info@lucacyvita.shop

## Características

- Catálogo completo de productos con filtros por categoría
- Cada producto enlaza directo a WhatsApp con mensaje pre-rellenado
- Diseño premium responsive (móvil, tablet, desktop)
- Panel de administración integrado para gestionar productos sin tocar código
  - Acceso: `Ctrl + Alt + A` o `?admin=1` en la URL
  - PIN por defecto: `1234`
  - Subir imágenes desde el dispositivo (con compresión automática)
  - Exportar / importar catálogo en JSON
- Imágenes optimizadas con lazy loading
- HTTPS y headers de seguridad configurados (vercel.json)

## Stack

- HTML5 + CSS puro + JavaScript vanilla
- Sin dependencias, sin build step, sin servidor
- Tipografía: Inter + Playfair Display (Google Fonts)
- Iconos: SVG inline

## Deploy

Compatible con cualquier hosting estático:

- **Vercel** (recomendado): arrastrar la carpeta a vercel.com/new
- **Netlify**: drag & drop
- **GitHub Pages**: push a `main` y activar Pages
- **Hostinger**: subir `index.html` a `public_html/`

## Estructura

```
lucacy-vita-deploy/
├── index.html       # Landing completa (single-file)
├── vercel.json      # Configuración de Vercel (caché + seguridad)
└── README.md        # Este archivo
```

## Editar productos

Abre la página en cualquier navegador → presiona `Ctrl + Alt + A` → ingresa PIN `1234` → gestiona productos desde el panel.

Los cambios se guardan en `localStorage` del navegador. Para sincronizar entre dispositivos, usa **Exportar JSON** y **Importar JSON**.

---

© 2026 Lucacy Vita · Todos los derechos reservados
