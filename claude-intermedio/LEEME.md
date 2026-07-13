# Claude para tu negocio · Intermedio — COCO GO

- **URL viva (tras publicar):** https://coco-go.github.io/claude-intermedio/
- **Módulos:** 7 (El salto · Delegá trabajos completos · Ponelo en piloto automático · Conectá Claude a tus herramientas · La memoria grande del negocio · Tu sistema que trabaja solo · Asomate a Claude Code)
- **Tabs totales:** 12 (Inicio, Aplicaciones, Glosario, 7 módulos, Verificación, Bonus)
- **Código de acceso:** `COCO-CLDINT-2026` (query param `?k=COCO-CLDINT-2026` o tipeado en el gate; distinto del básico `COCO-CLD7-2026`)
- **Glosario:** 40 términos, en 6 grupos temáticos.
- **Fuente del contenido:** `src/productos/claude/curso-intermedio/` (modulo-01..07.md + fijos.md) — no se editó, solo se maquetó.

## Componentes visuales nuevos (creados para este curso)
Agregados de forma aditiva a `assets/style.css` (no rompen los otros cursos):
- `.coworkmock` — flujo Cowork: describir → plan propuesto → aprobar/ajustar → ejecutando.
- `.schedulemock` — panel "Scheduled" / tarjeta de tarea con frecuencia y estado.
- `.connectorsmock` — grilla de conectores (Notion/Canva/Stripe/Linear) + estado conectado.
- `.projectmock` — Project con archivos de base de conocimiento + indicador RAG.
- `.modelmock` — selector de modelo (Sonnet 5 / Fable 5), pantalla de upgrade y Settings > Usage.
- `.codemock` — vista panorámica de Claude Code (dark/terminal, a propósito distinto del resto del curso).
- `.freqchips`, `.routinetable`, `.faltanote` — utilitarios menores (frecuencia, tabla de rutina, avisos ⚠️FALTA).

## ⚠️FALTA pendiente
- **og.png (1200×630):** no se generó el binario — el HTML referencia `og.png` con comentario `<!-- FALTA og.png 1200x630 -->` en el `<head>`. Falta crear y subir la imagen antes de publicar para que el share preview funcione.
- Los `⚠️FALTA` de contenido (nº máximo de tareas agendadas, vencimiento de permisos de conector, uso incluido exacto) vienen del contenido fuente y están marcados en el HTML tal cual — no se inventó ningún dato.

## No se tocó
- Ningún otro curso (`claude/`, `chatgpt/`, `gemini/`, `grok/`).
- El contenido `.md` fuente.
- No se hizo push — el commit no publica (`00-sistema/publicar.sh` + PUBLICAR lo hace Pablo).
