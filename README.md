Especificaciones para el archivo CSS:

* Encabezado (header) con sticky:

- Usa position: sticky para que el encabezado siempre esté visible.
- Añade un fondo de color y un relleno para que sea claro que está fijo.

* Barra de Navegación (nav) con sticky:

- Usa position: sticky ajusta el top y left para desplazarlo ligeramente, y que quede debajo de header
- Dale estilo a la lista de navegación para que los enlaces se muestren horizontalmente.

* Botón en la Segunda Sección (button) con absolute:

- Usa position: absolute para posicionar el botón en la esquina inferior derecha de cada sección.
- Asegúrate de que el contenedor de la sección tenga position: relative para que el botón se posicione correctamente.

Pie de Página (footer) con fixed:

Usa position: sticky y ajusta bottom: 0 para que el pie de página se quede "pegado" a fondo de la página, asegúrate que el footer no tape la última sección al llegar a final del scroll.
