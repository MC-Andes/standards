# Guía de contribución

¡Gracias por contribuir a MC-Andes!

## Flujo

1. Abre un issue (`bug`, `feature` o `question`) o toma uno existente.
2. Acordar el alcance antes de una implementación grande.
3. Crea una rama corta desde `main`: `feat/...`, `fix/...`, `docs/...` o
   `chore/...`.
4. Implementa el cambio junto con sus pruebas y documentación.
5. Abre un Pull Request usando la plantilla y enlaza el issue.
6. Atiende la revisión y conserva la CI en verde.

## Requisitos mínimos

- CI en verde.
- Cambios documentados en README/docs cuando aplique.
- Pruebas para cambios funcionales.

## Estilo

- Commits: Conventional Commits.
- Nombres claros en ramas, archivos y PR.
- Mensajes de PR con contexto técnico y validación.

## Definition of Done

- [ ] Las pruebas pasan y cubren el comportamiento modificado.
- [ ] El lint y los chequeos estáticos pasan.
- [ ] La documentación y los ejemplos están actualizados.
- [ ] `CHANGELOG.md` está actualizado cuando el cambio afecta usuarios.
- [ ] No se incorporaron secretos, datos sensibles ni artefactos generados.
- [ ] El Pull Request tiene la aprobación requerida y todos los checks verdes.

## Revisión

Los autores no aprueban su propio cambio. El revisor comprueba corrección,
reproducibilidad, claridad, rendimiento cuando aplique y compatibilidad con la
licencia de dependencias y datos.
