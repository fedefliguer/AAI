# Aprendizaje Automático Interpretable
## Editar el contenido
El primer paso es descargar los archivos de este repositorio y modificar o ir agregando los archivos .Rmd que compongan la totalidad del libro. Una vez hecho, deben modificarse los archivos **\_bookdown.yml** y **\_output.yml** para proceder a Knitear.
El primer paso es descargar los archivos de este repositorio y modificar o ir agregando los archivos .Rmd que compongan la totalidad del libro. Una vez hecho, deben modificarse los archivos **\_bookdown.yml** (cambiando los nombres de los capítulos, y el prefijo chapter por Capítulo) **\_output.yml** para proceder a Knitear.

## Publicación
Cuando el archivo esté completo, en R es momento de abrir el archivo **index.Rmd**, que va a contener el prefacio y los elementos básicos de configuración del libro. Con la librería bookdown instalada, corriendo **bookdown::render_book("index.Rmd")** ya debería generar, en la carpeta **\_book** o la especificada en **\_bookdown.yml**, cada uno de los archivos html de los capítulos individuales y el archivo index.html, que al abrirlo será el libro. 
