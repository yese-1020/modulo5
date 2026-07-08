# Checklist de Seguridad IA/n8n - Semana 10

## Variables y secretos

- [x] `.env` no está en GitHub.
- [x] `.gitignore` contiene `.env`.
- [x] No se subieron API keys.
- [x] No se subieron tokens de Telegram.
- [x] No se subieron claves compartidas.
- [x] Las credenciales se guardan en n8n o entorno seguro.

## IA

- [x] No se envían datos reales a DeepSeek.
- [x] No se envían datos sensibles.
- [x] El prompt prohíbe inventar hechos.
- [x] El prompt prohíbe inventar pruebas.
- [x] El texto generado se considera borrador.

## n8n

- [x] Webhook documentado.
- [x] URL de prueba no se publica con datos sensibles.
- x ] URL de producción queda pendiente o protegida.
- [ ] Se usa clave compartida si aplica.
- [x] Se documentan bloqueos.

## Google

- [x] Google Docs no se comparte públicamente con datos reales.
- [x] Google Sheets no guarda secretos.
- [x] Solo se usan datos de práctica.

## Telegram

- [x] El mensaje es no sensible.
- [x] No se envía texto completo.
- [x] No se envían documentos de identidad.
- [x] No se envían hechos delicados.