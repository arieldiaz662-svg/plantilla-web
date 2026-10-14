# Plantilla web (Next.js + TypeScript + Tailwind)

## Reglas
- Antes de dar una página o componente por terminado, ejecuta la skill `web-design-guidelines` sobre los archivos tocados y corrige lo que reporte.
- Usa App Router (`src/app`), TypeScript estricto y Tailwind.
- Accesibilidad primero: etiquetas en formularios, foco visible, contraste, `alt` en imágenes.

## Comandos
- `npm run dev` · `npm run build` · `npm run lint`

## Verificación en navegador
- Al terminar una página, usa la skill `playwright-skill` para abrirla con el dev server y revisar capturas en 375px, 768px y 1280px. Corrige solo lo que veas roto: desbordes, texto cortado, botones no clicables.
- Setup (una vez por máquina): `cd .claude/skills/playwright-skill && npm run setup`. No subas `node_modules` al repo.

## Orden de las skills de diseño (una por fase, para que no se contradigan)
1. **Dirección**: `design-taste-frontend` al empezar una landing o página pública (no para dashboards).
2. **Construcción**: `emil-design-eng` y `animate` para detalles y movimiento; `mobile-native` para lo táctil.
3. **Revisión**: `review-animations` y `animation-performance` sobre el movimiento; `web-design-guidelines` sobre accesibilidad.
4. **Verificación visual**: `playwright-skill` con capturas en 375/768/1280 px.
- Si dos skills discrepan, gana la de la fase más tardía solo en accesibilidad; en estética, la de dirección.
- Atribuye las fotos que `design-taste-frontend` descargue (guarda los créditos que genera).
