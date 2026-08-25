# Estándares de MC-Andes

Este repositorio define la base organizacional de **MC-Andes** para proyectos de
mecánica computacional. Las normas priorizan reproducibilidad, revisión por pares,
documentación técnica y automatización mínima.

## Decisiones comunes

| Tema | Estándar |
| --- | --- |
| Rama por defecto | `main` |
| Integración | Pull Request obligatorio |
| Commits | [Conventional Commits](https://www.conventionalcommits.org/) |
| Versionado | [Semantic Versioning](https://semver.org/) |
| Licencia por defecto | MIT, salvo requisito institucional distinto |
| Calidad | lint, pruebas y documentación en verde |

## Documentos

- [Gobernanza](GOVERNANCE.md)
- [Contribución](CONTRIBUTING.md)
- [Estrategia de ramas](BRANCHING.md)
- [Releases](RELEASE.md)
- [Seguridad](SECURITY.md)
- [Código de conducta](CODE_OF_CONDUCT.md)
- [Cómo crear un proyecto](NEW_PROJECT_CHECKLIST.md)

## Repositorios plantilla

- [`template-python-mech`](https://github.com/MC-Andes/template-python-mech)
- [`template-cpp-mech`](https://github.com/MC-Andes/template-cpp-mech)
- [`template-docs`](https://github.com/MC-Andes/template-docs)

Los cambios a estas normas se proponen mediante issue y Pull Request. Las
excepciones deben quedar justificadas en el README del proyecto afectado.
