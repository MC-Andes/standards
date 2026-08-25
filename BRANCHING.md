# Estrategia de ramas y Pull Requests

## Modelo recomendado

- `main`: rama estable y protegida.
- ramas cortas por cambio: `feat/...`, `fix/...`, `docs/...`, `chore/...`.

## Reglas de merge

- No se permite push directo a `main`.
- Todo cambio entra por PR.
- Al menos 1 aprobación de maintainer.
- Checks de CI obligatorios en verde.
- Las aprobaciones se descartan cuando se agregan cambios nuevos.
- Se recomienda squash merge para mantener un historial legible.
- Las conversaciones de revisión deben quedar resueltas antes del merge.

## Commits

Usar **Conventional Commits**:

- `feat:` nueva funcionalidad
- `fix:` corrección
- `docs:` documentación
- `refactor:` refactor sin cambio funcional
- `test:` pruebas
- `chore:` tareas de mantenimiento

Los cambios incompatibles incluyen `!` (por ejemplo, `feat!:`) y una nota
`BREAKING CHANGE:` en el cuerpo del commit.

## Hotfixes

Un hotfix sigue usando Pull Request. Si la urgencia obliga a reducir la ventana
de revisión, el maintainer documenta el motivo y abre un issue de seguimiento.
