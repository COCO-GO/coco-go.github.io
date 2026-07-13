# Gemini para tu negocio · Intermedio — COCO GO

**Estado:** HTML completo (7 módulos + fijos). Sin push hasta verif DISEÑO ≥80 + PUBLICAR.

## URL (cuando se publique)
`https://coco-go.github.io/gemini-intermedio/?k=COCO-GEMINT-2026`

## Código de acceso
`COCO-GEMINT-2026`  
localStorage: `coco-go-gemini-intermedio-access-ok`

## Qué incluye
7 módulos + Glosario (~76) + Aplicaciones + Bonus + Verificación:

1. El salto: de usar a mano a sistema que se repite  
2. Tu Gem con la cabeza del negocio  
3. Piloto automático  
4. Notebooks de proyecto  
5. Gemini donde ya trabajás  
6. Tu sistema Google que se repite  
7. Tu ficha y tus clientes en Google  

Fuente: `src/productos/gemini/curso-intermedio/` · contenido **94/100 PASA**.

## Precio lista
**US$17,99** (Creem al lanzar).

## Diseño
- Shell: `claude-intermedio` + theme Gemini `#4285F4`
- CSS: `../assets/style.css` (sin override de `.next`)
- CTA catálogo: `.app.curso-cta` + `.cta-curso` a la derecha (regla de marca)
- Cierre de módulo: `.next` (kicker + h3 coral + `.go`) → **replicar en todos los cursos**
- Instagram: `@coco-go.app`

## Probar local
```bash
cd coco-go.github.io && python3 -m http.server 8765
# http://127.0.0.1:8765/gemini-intermedio/?k=COCO-GEMINT-2026
```
No usar `file://` (rompe CSS).

## og:image
Provisional: `../gemini/assets/og-image.png`. Hacer `og.png` 1200×630 propio antes de lanzar.
