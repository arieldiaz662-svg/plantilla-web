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
