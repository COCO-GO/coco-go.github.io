# Curso "Grok para tu negocio" (básico) — COCO GO

**URL viva:** https://coco-go.github.io/grok/

## Acceso
- Código de acceso: `COCO-GRK7-2026`
- Magic link (entra solo, sin tipear código): https://coco-go.github.io/grok/?k=COCO-GRK7-2026
- El código queda recordado en el navegador (localStorage) después de la primera entrada.

## Precio
USD 17 → USD 12 de lanzamiento.

## Contenido — 7 módulos
1. Entrás y conocés Grok — cuenta creada, pantalla reconocida, puerta elegida, privacidad decidida.
2. Grok conoce tu negocio — Personaliza a Grok con tono, precios y políticas reales.
3. Grok al día: tu radar — búsqueda en vivo con Fuentes citadas + decisión anotada.
4. Grok con tus papeles — 1 documento real subido y analizado.
5. Grok te hace las imágenes — 2-3 piezas visuales con Grok Imagine, con edición conversacional por follow-ups (requiere X Premium, desde ~USD 5-8 según el país).
6. Grok conectado y con tu forma — 1 Connector (Gmail/Drive/Calendar) + 1 Skill propia.
7. Tu sistema Grok — rutina semanal + puerta elegida con criterio + uso seguro.

Más: Glosario (62 términos), Aplicaciones por área de negocio, Bonus (con guía de usabilidad y checklist anti-alucinación de 7 puntos), Verificación final.

## Estructura del archivo
- `index.html` — curso completo, autocontenido. Link a `../assets/style.css` (compartido, no tocar) +
  bloque `<style>` inline con la paleta Grok y los componentes nuevos del curso: `.grokmock` (chat con
  avatar negro + logo Grok), `.gate-badge` (sello 🆓/💲/💰 de las 3 puertas), `.antesdespues` (bloque
  sin/con del módulo 3), `.sysdiagram` (diagrama de cajas del módulo 7, fiel al ASCII fuente).
- Paleta (`:root`): `--theme:#111111; --theme-dark:#000000; --theme-light:#C4C7CC; --theme-rgb:120,124,130`.
- Gate, canvas de fondo, tabs por radios, brandbar, nav, paneles y footer: mismo patrón que `../gemini/index.html`.

## Cross-sell
Catálogo al pie con ChatGPT, Claude y Gemini — logos reales, links funcionando a `../chatgpt/`,
`../claude/`, `../gemini/`.

## Pendiente
- (resuelto 2026-07-10) `grok/assets/og-image.png` generada (1200×630, tema plata, patrón de los otros cursos); el meta `og:image` ya apunta bien.
