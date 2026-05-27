# LDC Rate Request — Sales Tool

Formulario interno de LDC (Logistic Dynamics Corporation) para que el equipo de ventas capture solicitudes de tarifas / leads y los envíe al área de pricing en formato consistente (texto para Outlook o imagen).

## Para el equipo de ventas

Abre la URL desplegada, llena el formulario, y usa los botones:

- **Copy as text** — copia un bloque HTML listo para pegar en Outlook con `Ctrl+V`.
- **Copy as image** — copia el formulario como imagen PNG para pegar en Outlook o WhatsApp.
- **Print** — imprime o guarda como PDF.
- **Reset** — limpia el formulario.

Los puertos tienen autocompletado (POL, POD, etc.) y puedes agregar múltiples rutas con el botón **+**.

## Para mantenimiento

Es un static site de un solo archivo (`index.html`). Para actualizar:

1. Edita `index.html` localmente o directamente en GitHub.
2. Haz commit a `main`.
3. Vercel redespliega automáticamente en ~30 segundos.
4. El equipo ve la nueva versión al refrescar el navegador.

No requiere build ni dependencias.
