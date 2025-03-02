# Portfolio Joaquín Sorolla - Práctica HTML/CSS

Proyecto de portfolio con una pequeña muestra de las obras de Joaquín Sorolla.

El proyecto simula que el artista ha abierto una modesta (tremendamente modesta) web para dar a conocer su trabajo, dividiéndola en dos páginas:

- Principal: 
    - **Barra de navegación** con su firma como imagen enlazada al Index, botones de enlazado a las propias secciones mostradas en la página.
    - Breve **texto de presentación** escrito en primera persona.
    - Sección de estilos con **barras de progreso** mostrando su pericia en distintos estilos.
    - **Banner** con imagen y texto que enlaza con la segunda página: Galería.
    - **Formulario de contacto** con las validaciones correspondientes y botones de guardado y borrado.
    - **Footer** con enlaces a recursos externos.

- Galería:
    - Repite la barra de navegación pero sin botonadura y el footer.
    - **Vídeo** con animación de fade in que no he conseguido mostrar con autoplay (he insertado en el link del embed el acabado ?autoplay=1&mute=1, pero tras probarlo en 3 navegadores distintos, modos de incógnito, etc., en ninguno reliza autoplay. Agradeceré feedback a este respecto).
    - **Grid** con una pequeña muestra de obras con imagen y título. Todas ellas enlazan a la propia imagen para permitir verlas con detalle.

Las dos páginas se han desarrollado con la perspectiva mobile first, y presentan variaciones significativas al llegar a los 768px de ancho a través de las pertinentes media queries.