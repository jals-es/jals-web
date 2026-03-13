# jals.es — Web personal de Juan Antonio López Seguí

Landing page personal diseñada y desarrollada **íntegramente con Inteligencia Artificial en menos de 1 hora**.

## El proceso

Esta web es una demostración real de lo que se puede conseguir combinando las herramientas de IA adecuadas. Todo el proceso — desde el diseño visual hasta el código final desplegable — se ha completado en una sola sesión de trabajo con IA.

### Herramientas utilizadas

| Fase | Herramienta | Descripción |
|------|-------------|-------------|
| **Diseño** | [Pencil](https://pencil.cc) + Claude | Diseño completo de la landing (desktop + mobile) en formato `.pen`, generado y refinado con IA |
| **Desarrollo** | [Claude Code](https://claude.ai) (Opus) | Lectura del diseño via MCP, generación del HTML/CSS completo, optimización SEO y verificación visual |
| **Verificación** | Chrome DevTools MCP | Screenshots automáticos para validar la fidelidad del diseño en desktop y mobile |

### Flujo de trabajo

1. **Diseño con IA** — Se generó el diseño completo en Pencil (desktop 1440px + mobile 390px) usando Claude como motor creativo. Paleta oscura con acento amarillo (#F5E642), tipografías Newsreader, Inter y JetBrains Mono.

2. **Lectura del diseño** — Claude Code leyó el archivo `.pen` mediante el MCP de Pencil, extrayendo la estructura completa: nodos, colores, tipografías, layouts, contenido e imágenes.

3. **Generación de código** — A partir del diseño, se generó el HTML semántico y CSS responsive en una sola pasada, respetando fielmente todos los detalles visuales del diseño original.

4. **SEO optimizado** — Se añadieron meta tags, Open Graph, Twitter Cards, Schema.org (JSON-LD) y HTML semántico optimizado para búsquedas como "jals", "juan antonio lópez seguí", "programador web ontinyent", etc.

5. **Verificación visual** — Se usó Chrome DevTools via MCP para tomar screenshots automáticos y comparar el resultado con el diseño original tanto en desktop como en mobile.

6. **Iteración en tiempo real** — Los ajustes al diseño en Pencil se reflejaron inmediatamente en el código: Claude detectó los cambios (botones de WhatsApp, icono de teléfono en footer) y actualizó el HTML automáticamente.

## Tech Stack

- **HTML5** semántico
- **CSS3** con Flexbox/Grid y responsive design
- **Google Fonts** — Newsreader, Inter, JetBrains Mono
- **Lucide Icons** — iconos SVG ligeros
- **Zero JavaScript frameworks** — JS mínimo para menú mobile e iconos

## Estructura

```
jals.es/
├── index.html          # Landing page completa
├── styles.css          # Estilos responsive
├── images/
│   ├── icono.png       # Logo/favicon
│   └── foto_jals.png   # Foto personal
├── jals-es.pen         # Archivo de diseño original (Pencil)
└── README.md
```

## Secciones

- **Header** — Logo + navegación + CTA
- **Hero** — Presentación con foto y badge "AI-POWERED DEVELOPER"
- **Sobre mí** — Bio + estadísticas
- **Servicios IA** — Desarrollo SaaS, Automatizaciones, Consultoría
- **Tech Stack** — IA & LLMs, Desarrollo, Infra & Tools
- **Proyectos** — 4 proyectos con cards visuales
- **CTA** — Contacto por Email y WhatsApp
- **Footer** — Links sociales

## SEO

Optimizado para las siguientes búsquedas:
- `jals`
- `juan antonio lópez seguí`
- `programador web ontinyent`
- `desarrollador web valencia`
- `programador ia valencia`

Incluye Schema.org Person + WebSite, Open Graph, meta tags y HTML semántico.

---

**100% diseñado y desarrollado con IA** — Claude Code (Opus) + Pencil MCP + Chrome DevTools MCP

© 2026 Juan Antonio López Seguí
