# Política de releases

## Versionado

Los proyectos usan Semantic Versioning: `vMAJOR.MINOR.PATCH`.

- `MAJOR`: cambio incompatible.
- `MINOR`: funcionalidad compatible.
- `PATCH`: corrección compatible.

Antes de `v1.0.0`, los cambios incompatibles deben resaltarse en las notas de
release y pueden incrementar `MINOR`.

## Proceso

1. Confirmar CI verde en `main`.
2. Actualizar `CHANGELOG.md`, documentación y metadatos de citación.
3. Crear un Pull Request de release.
4. Tras el merge, crear un tag firmado o verificable `vX.Y.Z`.
5. Publicar GitHub Release con cambios, compatibilidad y pasos de migración.
6. Verificar artefactos y documentación publicada.

Las entradas de changelog usan las categorías Added, Changed, Deprecated,
Removed, Fixed y Security cuando apliquen.
