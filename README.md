This is the absolute minimum you need to start a [bookdown](https://bookdown.org/yihui/bookdown/) book. You can find the
preview of this book at http://seankross.com/bookdown-start/

All of the content of this repository is licensed 
[CC0](https://creativecommons.org/publicdomain/zero/1.0/).

# Aprendizaje Automático Interpretable
## Editar el contenido
El primer paso es descargar los archivos de este repositorio y modificar o ir agregando los archivos .Rmd que compongan la totalidad del libro. Una vez hecho, deben modificarse los archivos **\_bookdown.yml** y **\_output.yml** para proceder a Knitear.

## Publicación
Cuando el archivo esté completo, en R es momento de abrir el archivo **index.Rmd**, que va a contener el prefacio y los elementos básicos de configuración del libro. Con la librería bookdown instalada, corriendo **bookdown::render_book("index.Rmd")** ya debería generar, en la carpeta **\_book** o la especificada en **\_bookdown.yml**, cada uno de los archivos html de los capítulos individuales y el archivo index.html, que al abrirlo será el libro.
