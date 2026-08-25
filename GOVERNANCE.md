# Gobernanza MC-Andes

## Alcance

Estas reglas aplican a los repositorios mantenidos por la organización. Un
proyecto puede añadir controles más estrictos, pero no reducirlos sin una
decisión documentada del equipo `core-maintainers`.

## Roles

- **Core Maintainers**: definen lineamientos técnicos, administran repositorios,
  aprueban cambios críticos y gestionan releases.
- **Research Contributors**: proponen e implementan cambios mediante Pull
  Requests y mantienen pruebas y documentación.
- **External Collaborators**: apoyan colaboraciones puntuales con permisos
  mínimos y revisión de maintainers.

## Principios

- Transparencia técnica (issues, PRs, decisiones documentadas).
- Reproducibilidad (ejemplos, pruebas, documentación).
- Calidad continua (CI obligatoria para merge).
- Escalabilidad por estandarización (templates + políticas comunes).

## Decisiones de base

- Rama principal: `main`
- Flujo: Pull Request obligatorio
- Convención de commits: Conventional Commits
- Versionado: Semantic Versioning (SemVer)

## Decisiones

1. Las decisiones reversibles se toman en un issue o Pull Request.
2. Las decisiones que afecten varios repositorios requieren aprobación de al
   menos un integrante de `core-maintainers`.
3. Los cambios incompatibles deben incluir plan de migración y versión mayor.
4. Los conflictos de interés deben declararse y la revisión debe reasignarse.

## Mantenimiento

- Los permisos se revisan cada seis meses y al finalizar una colaboración.
- Las plantillas y dependencias se auditan mensualmente.
- Un repositorio sin mantenimiento activo debe declararlo en su README y
  señalar una alternativa o plan de archivo.
