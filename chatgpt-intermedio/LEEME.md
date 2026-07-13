# ChatGPT para tu negocio · Intermedio — COCO GO

- **URL viva (tras publicar):** https://coco-go.github.io/chatgpt-intermedio/
- **Módulos:** 6 (El salto · Armá tu primer empleado · Cargale la memoria del negocio · Conectá tus herramientas · Que lea tus números · Ponelo en piloto automático) — la sección **Horizonte** (Work/Sites) NO cuenta como módulo.
- **Tabs totales:** 12 (Inicio, Aplicaciones, Glosario, 6 módulos, Horizonte, Verificación, Bonus)
- **Código de acceso:** `COCO-GPTINT-2026` (query param `?k=COCO-GPTINT-2026` o tipeado en el gate; distinto del básico `COCO-GPT...`). localStorage propio: `coco-go-chatgpt-intermedio-access-ok`. Progreso: `cocogo_progreso_chatgpt_intermedio`.
- **Progreso:** `/6` (la barra cuenta solo los 6 módulos; Horizonte tiene su check pero no suma a la barra).
- **Glosario:** 40 términos, en 8 grupos temáticos.
- **Paleta:** verde OpenAI — `:root{--theme:#10A37F; --theme-light:#34E0B0; --theme-rgb:16,163,127; --theme-dark:#0B7C60;}` (idéntica al básico `chatgpt/`).
- **Fuente del contenido:** `src/productos/chatgpt/curso-intermedio/` (modulo-01..06.md + fijos.md) — no se editó, solo se maquetó.

## Componentes visuales NUEVOS (creados para este curso)
Agregados de forma aditiva a `assets/style.css` (bloque "CURSO CHATGPT INTERMEDIO", tematizados por `var(--theme*)`, no rompen otros cursos):
- `.buildermock` — GPT Builder: pestañas Create/Configure, campos Name/Description/Instructions, Conversation starters, Knowledge, vista previa (M2).
- `.datamock` — análisis de datos: tabla + gráfico de barras en CSS puro, sin librerías (M5).
- `.workmock` — flujo ChatGPT Work: 3 estados en fila (delegar → trabajando… → entregable listo) (Horizonte).
- `.sitemock` — armado de un Site: descripción → vista previa de la página generada (Horizonte).
- `.permdialog` — diálogo de permisos "ChatGPT quiere acceder a…" (Podrá / No podrá + Cancelar/Permitir) (M4).
- Utilitario aditivo: reglas de visibilidad/pill para la pestaña extra `#t-horizonte`.

## Componentes REUTILIZADOS (ya en style.css, se ponen verdes solos con el :root)
`.modelmock` (M1 planes/upgrade, M4 nivel de permiso) · `.projectmock` (M3) · `.connectorsmock` (M4 grilla) · `.schedulemock` (M1, M6 panel Tareas) · `.gptmock` (chats de ChatGPT en todos los módulos) · `.uimock` (Config/Memoria M1, GPT Builder aux, instrucción de Tarea M6) · `.planes`, `.devsplit`, `.routinetable`/`.tablewrap`, `.faltanote`, `.foldertree`, gate/nav/footer del esqueleto `claude-intermedio/`. NO se redefinió ninguno.

## og:image
`og.png` (1200×630) generado con Chrome headless desde `og.html` — ✅ presente (no pendiente).

## Cómo probar local
Abrir `index.html` en el browser. Con `?k=COCO-GPTINT-2026` entra al curso; sin código, el gate tapa el contenido.

## No se tocó
- Ningún otro curso (`chatgpt/`, `claude/`, `claude-intermedio/`, `gemini/`, `gemini-intermedio/`, `grok/`).
- El contenido `.md` fuente en `src/productos/chatgpt/curso-intermedio/`.
- Ninguna regla CSS existente de `assets/style.css` (solo se agregó el bloque nuevo al final).
- **No se hizo push** — commit local; deploy = solo Pablo con PUBLICAR + `00-sistema/publicar.sh`.
