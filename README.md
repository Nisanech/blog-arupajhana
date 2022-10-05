# Descripción

  Página tributo para aplicar conceptos de HTML y CSS

<h1 align="center"> Blog Arupajhana </h1>

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/index.jpg)

# Bitácora de Registros

- Se dificultó la posición de la imagen como background ya que al colocarla no se podía visualizar 
  como se planteó en el mockup, sin embargo, se solucionó con la propiedad de background-size: cover, 
  esto haciendo que la imagen tomara todo el ancho disponible.
  
- Durante el desarrollo de esta sección se evidenció que las imágenes al tener tamaños diferentes hacían 
  que la cuadricula tomará diferentes posiciones al tratar de adaptarse al espacio disponible, sin embargo, 
  se solucionó haciendo que todo el contenido de la cuadricula se alineara a la base del contenedor evitando 
  así que el contenido se viera disparejo. Esto se presentó en el index.html.

- Durante el desarrollo del contenido de la página nueva_entrada.html se presentó mayor dificultad al dar estilos 
  al input para agregar la imagen, ya que al asignar un input type file el navegador asigna unos estilos por defecto, 
  debido a esto la personalización del input de acuerdo al mockup fue bastante complicado, se solucionó dejando el 
  input dentro de un div y con posicionamiento relativo y absoluto se generó el estilo indicado en el mockup. 
  Sin embargo, hacerlo de esta manera es crear un nuevo contenido con la propiedad before haciendo que se posicione 
  sobre el input pero sus estilos no cambiaron originalmente.
