# Hotel Narváez Ospino — Cartagena Sport Hotel

Sitio estático responsive en `index.html`, sin dependencias externas. Abrir directamente en un navegador o servir mediante GitHub Pages.

## Configuración
- Editar `const HOTEL = { whatsapp: "" };` en index.html con el número oficial verificado (57 seguido del número colombiano, sin espacios ni +). No usar un número de ejemplo en producción.
- Confirmar amenidades, dirección, horarios, distribución de las 100 habitaciones, camas, capacidades y tarifas antes de retirar los avisos de contenido conceptual.
- Sustituir las ilustraciones SVG por fotografías autorizadas del hotel si están disponibles.
- El concierge es un asistente local basado en reglas, no un LLM ni atención humana en vivo. No almacena mensajes ni confirma inventario. Para disponibilidad real se necesita un PMS o backend.
- El formulario genera una solicitud, no una reserva confirmada. WhatsApp requiere envío voluntario por el visitante.

## Publicación
En GitHub, Settings > Pages > Build and deployment > Deploy from a branch > main > / (root) > Save. Verificar la URL publicada en Settings > Pages.

## Comprobaciones manuales antes de publicar
- Navegación móvil y escritorio, teclado y foco visible.
- Botones de habitación preseleccionan la categoría.
- Llegada no anterior al día actual de Colombia; salida posterior a llegada.
- Sin número configurado, la solicitud se puede copiar y no se envía a terceros.
- Con número oficial configurado, verificar que WhatsApp abre con fechas y categoría correctas.
- Concierge: probar preguntas sobre habitaciones, amenidades, grupos, precios y preguntas desconocidas.

No se ha realizado aún una prueba visual en navegador ni se ha activado GitHub Pages desde este entorno.
