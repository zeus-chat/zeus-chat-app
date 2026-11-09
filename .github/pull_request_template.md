## Cambio
<!-- Qué cambia y por qué (en español). El título del PR es un Conventional Commit en inglés: feat(HU-10): show message delivery state -->

## Historia
<!-- HU-xx · ADR-NNN -->

## Checklist (Definition of Done)
- [ ] Desarrollado con TDD (tests primero, el historial de commits lo evidencia)
- [ ] Los criterios de aceptación de la historia están cubiertos por tests
- [ ] Probado contra el contrato (servidor *mock* o staging local); si el contrato cambió, `zeus-chat-docs` ya estaba actualizado
- [ ] Sin APIs exclusivas de web (`window`, `document`, `localStorage`) fuera de módulos `*.web.ts`
- [ ] ESLint, `tsc --noEmit` y Jest en verde (CI)
- [ ] Sin secretos ni tokens en el código; los mensajes se muestran como texto plano escapado
- [ ] Documentación afectada actualizada (README, ADR)
