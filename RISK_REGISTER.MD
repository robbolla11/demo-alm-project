# Registro de Riesgos - Pruebas

| ID  | Riesgo | Probabilidad (B/M/A) | Impacto (B/M/A) | Prioridad | Mitigación | Responsable | Estado |
|-----|--------|-----------------------|------------------|-----------|-----------|-------------|--------|
| R001| Fallo crítico en integración continua que permite merge a main con tests rotos | M | A | Alta | Protecciones de rama + checks obligatorios + pipeline que falla PR | @equipo-ci | Abierto |
| R002| Dependencia vulnerable no detectada | M | M | Media | Dependabot + revisión de avisos de seguridad | @security | Abierto |
