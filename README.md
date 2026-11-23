# Cartesian Welding Robot

**Open-source development of a Cartesian robotic platform for welding applications.**  
**Desarrollo de una plataforma robótica cartesiana de arquitectura abierta para aplicaciones de soldadura.**

> **Project status / Estado del proyecto:** Development and integration in progress / Desarrollo e integración en curso.

## Overview / Descripción

This repository organizes the mechanical design, electronics, software, simulation models, technical documentation, and experimental evidence for a Cartesian robot adapted for welding applications.

Este repositorio organiza el diseño mecánico, la electrónica, el software, los modelos de simulación, la documentación técnica y la evidencia experimental de un robot cartesiano adaptado para aplicaciones de soldadura.

The platform is based on an open Cartesian/CNC architecture and is being adapted through mechanical, electrical, and software integration. The system architecture and implemented capabilities will be documented as they are verified.

La plataforma parte de una arquitectura cartesiana/CNC abierta y se adapta mediante integración mecánica, electrónica y de software. La arquitectura y las capacidades implementadas se documentarán conforme sean verificadas.

## Repository structure / Estructura del repositorio

| Directory | Purpose |
|---|---|
| `docs/` | Bilingual technical documentation / Documentación técnica bilingüe |
| `mechanical/` | CAD, drawings, assemblies and bill of materials / CAD, planos, ensambles y lista de materiales |
| `electronics/` | Schematics, wiring and component information / Diagramas, cableado y componentes |
| `software/` | Robot software, motion planning, interpreter and GUI / Software, planificación, intérprete e interfaz |
| `simulation/` | URDF and simulation projects / URDF y proyectos de simulación |
| `experiments/` | Test procedures, raw data and processed results / Procedimientos, datos y resultados |
| `thesis/` | Thesis source and supporting material / Fuente de tesis y material complementario |

See [`docs/README.md`](docs/README.md) for the documentation map.

## Getting started / Primeros pasos

This repository is initially a documentation and project scaffold. Subsystems should include their own README with prerequisites, setup instructions, configuration, and verification steps before being considered ready for use.

Este repositorio comienza como una estructura base de documentación y desarrollo. Cada subsistema deberá incluir su propio README con requisitos, instalación, configuración y pasos de verificación antes de considerarse listo para utilizarse.

1. Review the subsystem documentation under `docs/`.
2. Check the status and prerequisites of the subsystem you intend to use.
3. Do not assume that an example, placeholder, or planned feature is implemented in the physical robot.

## Project status / Estado de desarrollo

| Subsystem | Status |
|---|---|
| Mechanical design | In development / En desarrollo |
| Electronics | In development / En desarrollo |
| Motion software | In development / En desarrollo |
| GUI | In development / En desarrollo |
| URDF and simulation | In development / En desarrollo |
| Experimental validation | Pending or ongoing / Pendiente o en curso |

Update this table only when the corresponding implementation or evidence is available.

## Documentation languages / Idiomas

Documentation is intended to be bilingual (Spanish and English). Where a page is not yet translated, the available language will be identified at the beginning of the document.

La documentación busca ser bilingüe (español e inglés). Cuando una página aún no esté traducida, se indicará el idioma disponible al inicio del documento.

## Contributing / Contribuciones

Before submitting changes:
- Keep CAD source files and exported neutral formats clearly identified.
- Include units, coordinate frames, and relevant assumptions in technical documents.
- Record hardware revisions and software versions.
- Do not upload credentials, access tokens, private keys, or personal data.
- Do not describe a feature as validated without recording its test procedure and evidence.

Antes de incorporar cambios:
- Identificar claramente los archivos CAD originales y sus formatos de intercambio.
- Incluir unidades, marcos de referencia y supuestos en los documentos técnicos.
- Registrar revisiones de hardware y versiones de software.
- No subir credenciales, tokens, llaves privadas ni datos personales.
- No declarar una función como validada sin registrar el procedimiento y la evidencia de prueba.

## License

No license has been selected yet. Until a license is added, do not assume that the contents may be redistributed, modified, or used commercially. See `docs/project_governance.md` before choosing a license.

Aún no se ha seleccionado una licencia. Mientras no se agregue, no debe suponerse que el contenido puede redistribuirse, modificarse o utilizarse comercialmente. Consulta `docs/project_governance.md` antes de elegirla.
