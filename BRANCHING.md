# Estrategia de ramas y Pull Requests

## Modelo recomendado

- `main`: rama estable y protegida.
- ramas cortas por cambio: `feat/...`, `fix/...`, `docs/...`, `chore/...`.

## Reglas de merge

- No se permite push directo a `main`.
- Todo cambio entra por PR.
- Al menos 1 aprobación de maintainer.
- Checks de CI obligatorios en verde.

## Commits

Usar **Conventional Commits**:

- `feat:` nueva funcionalidad
- `fix:` corrección
- `docs:` documentación
- `refactor:` refactor sin cambio funcional
- `test:` pruebas
- `chore:` tareas de mantenimiento
