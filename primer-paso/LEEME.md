# Primer paso con IA (curso FREE de entrada · ex-PRE)

Producto gratis de entrada del catálogo COCO GO. Puerta del funnel: despierta + 1-2 victorias
reales con el negocio del alumno, y lo rutea a **un** curso básico.

## Acceso

- **URL viva:** https://coco-go.lat/primer-paso/
- **Nombre anterior:** PRE · `/pre/` (redirect activo)
- **Acceso LIBRE, sin código** (`?k=`). Es el free: abierto a propósito, sin gate.
- Se sirve tal cual desde GitHub Pages (HTML/JS vanilla, sin build).

## Contenido

- **4 secciones** (anclas, no tabs):
  1. `#n1` — La estás usando como Google (buscar vs. hacer con tus datos)
  2. `#n2` — El patrón (contexto + tarea + formato)
  3. `#n3` — Tu resultado real (menú de 6 tareas + revisar + guardar) — corazón de la sesión
  4. `#n4` — ¿Con cuál seguís? (comparativa de las 4 herramientas + decisor interactivo)
- **Glosario** `#glosario` — «Para que ninguna palabra te frene»: **26 cards** (vocabulario de
  conversación). Botón flotante «¿Qué significa esto?» + términos subrayados en el cuerpo que
  abren su definición.
- **CTA final único** — alimentado por el decisor (3 preguntas → un básico), precio **US$11,99**.
  Link de compra por producto = checkout Creem del básico recomendado (ver `RedesGO/LINKS-CREEM.md`).
  Sin pack, sin grilla de 4 botones, sin links muertos.

## Diseño (gate visual cerrado por Pablo 2026-07-16)

- **Mundo CLARO CREMA** (primera vez en el catálogo): crema/blanco + texto navy + acento coral/ámbar.
- **Híbrido mapa + anclas**: mapa de 4 cards arriba (chip de tiempo) que anclan a cada sección.
- **Partículas SOLO en el hero** (pastel coral/ámbar, pocas, lentas, `pointer-events:none`) +
  micro-entrada CSS de cards. Respeta `prefers-reduced-motion`.
- CSS propio inline (mundo claro): **no toca `assets/style.css`** (los patrones nuevos entran a
  fábrica recién después del gate visual de Pablo).

## Archivos

- `index.html` — producto (autocontenido, CSS/JS inline; usa logos SVG de `../assets/`).
- `og.html` — plantilla OG 1200×630 (mundo claro). Falta renderizar `og.png` (lo hace el
  orquestador). Meta `og:image`/`twitter:image` ya apuntan a `https://coco-go.lat/primer-paso/og.png`.
- `LEEME.md` — este archivo.

## Pendiente antes de publicar

- Renderizar `og.png` (1200×630) desde `og.html` con Chrome headless y verificar `file og.png`.
- QA final §9 del protocolo + PUBLICAR de Pablo (commit ≠ publicar).

## Fuente del contenido

`02-proyectos/coco-go/src/productos/pre/curso-free/` (seccion-0..3.md + _glosario.md + fijos.md,
ya verificados 95/100). El MD es la fuente de verdad; el HTML es transferencia fiel.
