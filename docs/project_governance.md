# Project governance / Gestión del proyecto

## Repository visibility / Visibilidad

Initial target: private repository. Confirm the visibility in GitHub when creating the remote repository.

Objetivo inicial: repositorio privado. Confirmar la visibilidad en GitHub al crear el repositorio remoto.

## Languages / Idiomas

Use English for directory names, source-code identifiers, and filenames where practical. Provide Spanish and English documentation for important user-facing and technical guides. Do not duplicate every minor note unless it improves usability.

Usar inglés para nombres de directorios, identificadores de código y nombres de archivo cuando sea práctico. Mantener documentación en español e inglés para las guías técnicas y de usuario importantes.

## Versioning / Versionado

- Use Git commits for traceable changes.
- Use tags for stable releases.
- Record hardware revision and software version together when publishing a tested configuration.
- Do not use a release tag to imply validation unless the test evidence is included.

## CAD file policy / Política de archivos CAD

Git LFS decision is pending until representative file sizes and repository limits are reviewed. Keep native CAD files, neutral exports (STEP), drawings (PDF/DXF), and preview images clearly distinguished. Avoid committing temporary and autosave files.

La decisión sobre Git LFS queda pendiente hasta revisar tamaños representativos y límites del repositorio. Diferenciar archivos CAD nativos, exportaciones neutras (STEP), planos (PDF/DXF) e imágenes de vista previa. Evitar archivos temporales y de recuperación.

## License / Licencia

No license has been selected. Decide whether hardware designs, software, and documentation require the same or different licenses. Review ownership, institutional agreements, third-party components, and contributor permissions before publishing.

No se ha seleccionado una licencia. Determinar si los diseños de hardware, el software y la documentación requieren la misma licencia o licencias diferentes. Revisar titularidad, acuerdos institucionales, componentes de terceros y permisos de colaboradores antes de publicar.

## Contribution rules / Reglas de contribución

- Use descriptive commit messages.
- Include units and coordinate conventions.
- Record changes that affect interfaces.
- Attach test evidence for behavior changes.
- Never commit credentials or personal data.
