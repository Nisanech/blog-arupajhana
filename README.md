# Descripción

Página tributo para aplicar conceptos de HTML y CSS. 

El diseño de la página es tipo blog enfocado al Budismo con entradas sobre meditación, historia budista y libros escritos por monjes y monjas budistas.
  
# Despliegue de la página

https://blog-arupajhana.netlify.app

<h1 align="center"> Blog Arupajhana </h1>

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/index.jpg)

# Requerimientos

- Tema: Budismo.
- Estilo de la página: Blog.
- Funcionalidad: Crear entrada de blog.
- Funcionalidad: Visualizar entrada de blog.
- Funcionalidad: Comentar entradas de blog.
- Categorías del blog: Budismo, Meditación, Libros.
- Adaptabilidad: Móvil, Tablet y Escritorio.
- Tipografía: Libre elección.
- Paleta de colores: Relacionados con el budismo.
- Imágenes: Libre elección.

# Mockups

El mockup de la página se encuentra en la carpeta doc de este repositorio, en donde se encuentra la versión Móvil, Tablet y Escritorio. En el archivo de la versión móvil se encuentra la carta gráfica donde se indica la paleta de colores, la tipografía a utilizar y el uso del logo.

# Estructura del HTML

La estructuración del HTML se realizó de manera semántica y utilizando clases para la selección del elemento en el archivo CSS. Para el nombre de las clases de utilizó el enfoque BEM (Bloque__Elemento--Modificador).

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/code_semantico.JPG)
![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/code_BEM.png)

# Estructura del CSS

Los estilos de la página se realizaron con CSS Vanilla -sin uso de framework-, aplicando:

- Custom propierties para la paleta de colores y la tipografía.

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/code_custom-propierties.png)

- Selectores específicos.

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/code_selector.png)

- Media queries para el diseño responsive en Móvil, Tablet y Escritorio.

![Image text](https://github.com/Nisanech/blog-arupajhana/blob/main/img/code_media-queries.png)

# Bitácora de Registros

- Se dificultó la posición de la imagen como background ya que al colocarla no se podía visualizar 
  cómo se planteó en el mockup, sin embargo, se solucionó con la propiedad de background-size: cover, 
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
