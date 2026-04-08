# ThermalLabeler

**ThermalLabeler** es una utilidad para imprimir etiquetas en impresoras térmicas desde Android  
sin dependencia de un fabricante específico y sin controladores propietarios.

La aplicación actúa como un puente entre Android y la impresora térmica y proporciona control total sobre la impresión de etiquetas donde las soluciones estándar no funcionan o resultan incómodas.

La aplicación resuelve una tarea práctica:  
cómo imprimir una etiqueta desde un teléfono o tablet en una impresora térmica común en modo TSPL.

Antes de imprimir, el contenido del archivo se convierte automáticamente en un diseño rasterizado, se escala al tamaño real de la etiqueta y se prepara teniendo en cuenta la orientación, los márgenes y los parámetros de la impresora.

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
- impresión desde sistemas comerciales  
- impresión desde aplicaciones Android personalizadas  
