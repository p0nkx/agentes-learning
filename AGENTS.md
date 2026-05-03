# AGENTS.md - agentes-learning

Repositorio para documentar y aprender el uso de OpenCode y agentes de código AI.

## Stack y propósito

- **Repositorio simple**: HTML + Tailwind CSS (vía CDN). No hay build tools, npm, ni frameworks.
- **Página web principal**: `index.html` contiene tutorial, comandos y límites de OpenCode.
- **Documentación**: `README.md` con enlaces a recursos oficiales.

## Comandos de desarrollo

- Abrir la web localmente: abrir `index.html` en el navegador (no requiere servidor).
- Edición directa de `index.html` (Tailwind vía CDN: `https://cdn.tailwindcss.com`).

## Convenciones

- **Idioma**: Contenido en español, código en inglés (nombres de clases Tailwind).
- **Estilo**: HTML con Tailwind CSS, sin JavaScript adicional (salvo configuración de Tailwind inline).
- **Codificación**: UTF-8, saltos de línea CRLF (Windows).

## Notas para el agente

- No buscar `package.json`, `tsconfig.json` ni configuraciones de bundlers: no existen en este repo.
- Si se agregan nuevas páginas HTML, mantener el mismo patrón de Tailwind CDN y fuente Inter.
- Los archivos se commitean directamente; no hay linters ni tests configurados.
- El repo está en una carpeta de OneDrive (`C:\Users\elfab\OneDrive\Documentos\Webs\agente`).
