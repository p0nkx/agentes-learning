# agentes-learning

Repositorio para documentar y aprender el uso de OpenCode, Git y skills en el contexto de agentes de código AI.

## Estructura del proyecto
- **Single-page web**: `index.html` usa Tailwind CSS vía CDN (sin build tools ni frameworks). Contiene 3 pestañas con navegación animada:
  - **OpenCode**: Tutorial, comandos, límites de planes y gestión de sesiones
  - **Git**: Documentación completa (configuración, ramas, log, deshacer cambios, stash, sincronización, .gitignore, tags y flujos de trabajo). El antiguo `git-commands.html` fue eliminado y su contenido fusionado aquí.
  - **Skills**: Guía de instalación (global y por proyecto) y uso de skills en OpenCode
- `AGENTS.md`: Instrucciones para agentes de OpenCode que trabajen en este repositorio
- `README.md`: Este archivo, con descripción del proyecto y recursos útiles

## Comandos útiles

### OpenCode
```bash
# Inicializar OpenCode en el proyecto
opencode

# Comandos dentro de OpenCode
/help          # Ver ayuda
/init           # Inicializar proyecto
/connect        # Conectar proveedor de modelos
/sessions       # Cambiar entre sesiones
/undo           # Deshacer cambios
/redo           # Rehacer cambios
```

### Git
```bash
# Inicializar repositorio
git init

# Añadir cambios al staging area
git add .

# Crear commit
git commit -m "Descripción de los cambios"

# Sincronizar con remoto (usamos HTTPS para evitar errores de SSH)
git push origin main
```

## Recursos
- [Documentación oficial de OpenCode](https://opencode.ai/docs)
- [Repositorio de OpenCode en GitHub](https://github.com/anomalyco/opencode)
- [Directorio de Skills](https://skills.sh)
- [Repositorio de este proyecto](https://github.com/p0nkx/agentes-learning)
