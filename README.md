# Automatización de facturas Autosur

Repositorio de distribución para el actualizador del Cargador de Facturas Autosur.

## Seguridad

- Este repositorio no contiene contraseñas, credenciales, PDFs ni registros de facturas.
- Las credenciales permanecen cifradas en el Administrador de credenciales de Windows.
- Cada paquete se valida mediante SHA-256 antes de instalarse.
- Los datos operativos permanecen en las carpetas locales de trabajo.

## Actualizaciones

El programa consulta `update/manifest.json`, descarga el paquete indicado y conserva una copia de seguridad de la versión anterior.
