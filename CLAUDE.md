# Instrucciones para Claude en este repositorio

- **Bitácora obligatoria:** cada cambio o avance se registra en `docs/bitacora-del-trabajo.md`.
  Agregar un paso nuevo con qué se hizo, por qué y cómo se comprobó. Si aparecieron problemas,
  sumarlos a la tabla "Problemas que aparecieron al probar". Mantener al día las secciones
  "Cómo está organizado el repositorio hoy", "Estado frente al TP1" y "Próximos pasos".
- El grupo tiene poca experiencia con NestJS: explicar en español, paso a paso, y con los comandos
  exactos para probar en GitHub Codespaces. Recordar que cada terminal nueva arranca en la raíz y
  hay que hacer `cd m6-viajes`.
- Antes de commitear, correr desde `m6-viajes/`: `npm run typecheck`, `npm test`,
  `npm run test:postgres` (si hay PostgreSQL) y `npm run contratos:validar`.
