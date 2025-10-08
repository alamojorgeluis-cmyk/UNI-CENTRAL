# Uni-Central Demo

Este repositorio contiene una demo estática del portal **Uni-Central**. Todo el código de la interfaz vive en [`index.html`](index.html), por lo que no se necesita un entorno de construcción con React o Node para verlo funcionando.

## Ejecutar la demo localmente

Sigue estos pasos para abrir la aplicación en tu navegador:

1. Asegúrate de tener **Python 3** instalado. Viene incluido en la mayoría de los sistemas.
2. En la raíz del proyecto, ejecuta un servidor estático temporal con:
   ```bash
   python3 -m http.server 3000
   ```
3. Abre tu navegador y visita <http://localhost:3000/index.html>.

> También puedes abrir `index.html` directamente en el navegador (doble clic sobre el archivo). Sin embargo, usar un servidor local evita problemas de seguridad del navegador al cargar recursos externos.

## Detener el servidor

Cuando termines, regresa a la terminal donde iniciaste el servidor y presiona `Ctrl + C`.

## Contenido

- `index.html`: archivo único con todo el código HTML, CSS y JavaScript de la demo, incluyendo la lógica del bot, los modales y los componentes React cargados desde CDN.

¡Listo! Con estos pasos deberías poder "ejecutar" la demo sin necesidad de configurar un entorno adicional.
