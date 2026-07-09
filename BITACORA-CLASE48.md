# Bitácora Clase 48

## Datos

Nombre: Yesenia Bolaños
Fecha: 02-07-2026

Clase: 48
Rama GitHub: clase-48-formulario-peticion-node

## Comunicaciones

¿Qué tarjeta se trabajó en ClickUp?

- HU-03 - Crear formulario de derecho de petición
- HU-04 - Conectar Node.js con n8n

¿Qué criterios de aceptación se cumplieron?

¿Qué mensaje debe entender el usuario antes de generar el borrador?

## Jurídico

¿Qué datos mínimos pide el formulario?

- fecha
- ciudad
- entidad destinataria
- nombre del solicitante
- tipo de documento
- número de documento
- correo
- tipo de petición
- asunto

¿Qué datos no se deben usar en clase?

- datos reales

¿Por qué el documento sigue siendo un borrador?

## Tecnología

¿Qué archivos se crearon o modificaron?

- public/peticion.html
- public/css/styles.css
- public/js/peticion.js
- README-clase48.md
- BITACORA-CLASE48.md
- n8n.service.js
- peticiones.routes.js

¿Qué ruta POST se creó?

post /api/peticiones/generar

¿Qué significa modo mock?

que no se conectó a n8n; es cuando la app devuelve una respuesta simulada

¿Qué variable se usará para conectar n8n?

n8n_webhook_peticion

## Evidencia

¿Se generó vista previa local?

si

¿Se copió el borrador?

si

¿El backend respondió?

si

Commit realizado:

Clase 48 agrega formulario funcional y ruta peticiones

Estado final de la tarjeta ClickUp:
