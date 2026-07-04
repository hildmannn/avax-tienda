# Avax · Tienda de tecnología

Sitio web de **Avax**, tienda de celulares (sellados y usados), audio, smartwatches, tablets, accesorios y servicio técnico.

📍 **Rivadavia 147, Río Cuarto, Córdoba**
📞 **358 431-0722** · WhatsApp +54 9 358 431-0722

## Sobre el proyecto

Página estática de una sola vista (`index.html`) generada a partir de un diseño de Claude Design.
Incluye catálogo con filtros, carrito, checkout, cotizador de reparaciones e integración con WhatsApp.

- `index.html` — la página (React + runtime de Design Component, todo autocontenido)
- `assets/` — imágenes de productos, fuentes y librerías JS (sin dependencias externas)
- `source/Avax.original.html` — el bundle original del diseño, como respaldo

> Los productos y precios son de referencia (provienen de la plantilla del diseño).
> Se pueden editar en el bloque de datos `PRODUCTS` dentro de `index.html`.

## Desplegar

El sitio se publica con **GitHub Pages** desde la rama `main` (carpeta raíz).
