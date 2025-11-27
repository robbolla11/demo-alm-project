# Playbook de Incidentes

## Niveles de severidad
- S1 (Critico): servicio caída total / datos en riesgo → Notificar inmediatamente por llamada + abrir canal #incidentes
- S2 (Alto): degradación mayor → notificar, mitigación prioritaria
- S3/S4: menor impacto → triage y plan normal

## Pasos inmediatos (primeros 15 minutos)
1. Asigna owner (primer que responde).
2. Cambia etiqueta `status:investigating` en el issue.
3. Recolectar logs, reproductibilidad y scope (usuario afectado, porcentaje).
4. Aplicar mitigación temporal si existe.

## Comunicación
- Crear mensaje para status page / Slack con: resumen, impacto, acciones tomadas, ETA.
- Actualizar issue con cada avance cada 30 min!

## Postmortem
- Cuando esté resuelto: crear Postmortem (root cause, timeline, acciones preventivas) y asignar labels `root-cause`, `postmortem-done`.
