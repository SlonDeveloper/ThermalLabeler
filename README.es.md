# ThermalLabeler

**ThermalLabeler** es una aplicación para Android que permite imprimir en impresoras térmicas sin depender de controladores propietarios del fabricante.

<p align="center">
  <img src="images/roll.jpg" alt="Receipt roll" width="300">
</p>

Importante: la aplicación está diseñada exclusivamente para impresoras térmicas compatibles con los modos <b>TSPL</b> y/o <b>ESC/POS</b>:
<ul>
  <li><b>TSPL</b> - se utiliza para imprimir etiquetas autoadhesivas
  <li><b>ESC/POS</b> - se utiliza para imprimir en papel térmico en rollo (recibos, comprobantes, tickets y otros documentos)
</ul>
La aplicación no está diseñada para impresoras de oficina convencionales, de inyección de tinta, láser u otros tipos de impresoras y no funciona con ellas. Solo se admiten impresoras térmicas con una interfaz de impresión compatible con <b>TSPL</b> y/o <b>ESC/POS</b>.
<BR>
<BR>La aplicación actúa como un puente entre Android y la impresora térmica, proporcionando un control total sobre la impresión de etiquetas y documentos en papel térmico en rollo cuando las soluciones estándar no funcionan o presentan limitaciones. Resuelve un problema práctico: cómo imprimir una etiqueta o un documento desde un teléfono o una tableta en una impresora térmica compatible.
<BR>
<BR>Antes de imprimir, el contenido del archivo se convierte automáticamente en una imagen rasterizada.
<BR>Al imprimir etiquetas, la imagen rasterizada se ajusta al tamaño real de la etiqueta teniendo en cuenta la orientación, los márgenes y la configuración de la impresora. Al imprimir en una impresora de recibos, la imagen rasterizada resultante se ajusta al ancho del papel.

---

## Plantillas de etiquetas

En la aplicación se pueden crear y guardar múltiples plantillas de etiquetas con diferentes tamaños y parámetros de impresión.

Cada plantilla incluye un conjunto de propiedades:

- ancho y alto de la etiqueta  
- espacio entre etiquetas (gap)  
- desplazamiento  
- orientación y rotación  
- parámetros de alineación  
- preimpresión (zona no imprimible)  

Las plantillas creadas se reutilizan y permiten cambiar rápidamente entre distintos tipos de etiquetas sin necesidad de volver a configurar.

---

## Impresión directa

La impresión se realiza directamente:

- mediante Bluetooth  
- mediante USB  
- mediante Wi-Fi  

La aplicación permite abrir archivos (PDF, HTML, imágenes) directamente desde el sistema Android.

Al seleccionar «Abrir con» o «Compartir», el archivo se carga automáticamente en la aplicación y se prepara para la impresión.

---

## Integración con Android PrintService

La aplicación funciona como un servicio de impresión de Android (PrintService):

- disponible en el cuadro de diálogo estándar «Imprimir»  
- puede ser utilizada por cualquier aplicación (programas comerciales, navegadores, visores de PDF, etc.)

---

## Formatos de archivo compatibles

La aplicación permite abrir e imprimir etiquetas desde los siguientes tipos de archivos:

- **PDF** — documentos y diseños obtenidos de otras aplicaciones o sistemas  
- **HTML** — páginas y plantillas, incluidos informes y etiquetas generados automáticamente  
- **Imágenes** — PNG, JPG y otros formatos comunes  

---

## Historial de impresión

La aplicación guarda el historial de los trabajos de impresión realizados.

Para cada trabajo se registran:

- el archivo original  
- los parámetros de impresión  

Desde el historial se puede volver a abrir un trabajo y repetir la impresión sin necesidad de seleccionar nuevamente el archivo o configurar los parámetros.

---

## Diferencias respecto a las soluciones «convencionales»

- sin emulación de A4  
- sin dependencia de una marca específica de impresora  
- impresión precisa «etiqueta a etiqueta»  
- control total del flujo de impresión  
- adecuado para almacenes, tiendas, logística y etiquetado  

---

## Escenarios de uso típicos

- impresión de etiquetas de precios y códigos de barras  
- impresión de etiquetas de almacén y transporte
- Impresión de recibos y otros documentos en papel térmico en rollo
- impresión desde sistemas comerciales  
- impresión desde aplicaciones Android personalizadas  
