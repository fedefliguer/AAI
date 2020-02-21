# Aprendizaje Automático Interpretable
## Editar el contenido
El primer paso es descargar los archivos de este repositorio y modificar o ir agregando los archivos .Rmd que compongan la totalidad del libro. Una vez hecho, deben modificarse los archivos **\_bookdown.yml** (cambiando los nombres de los capítulos como queremos que los incluye, y el prefijo chapter por Capítulo) **\_output.yml** (el split_by) para proceder a Knitear.

## Publicación
Cuando los archivos estén corregidos, en R es momento de abrir el archivo **index.Rmd**, que va a contener el prefacio y los elementos básicos de configuración del libro. Con la librería bookdown instalada, corriendo **bookdown::render_book("index.Rmd")** ya debería generar, en la carpeta **\_book** o la especificada en **\_bookdown.yml**, cada uno de los archivos html de los capítulos individuales que estén en la carpeta y el archivo index.html, que al abrirlo será el libro. 

## Github
Para que pueda verse en github, en bookdown.yml debe setearse **output_dir: "docs"** lo que significa que el archivo irá a esa carpeta, junto al resto de los archivos. Una vez hecho eso el contenedor está completo, y puede subirse a un repositorio github, que en los settings tiene que cambiar el Source a **“master branch/docs folder”**. Dentro de github, es necesario en la carpeta 'docs' generar un archivo vacío de nombre **.nojekyll**. Una vez con la carpeta, se sube a GitHub desktop y se hace un commit, actualizando todo el repositorio. Si todo el contenedor se sube de esta manera a Github, entonces la URL que se muestra en settings como URL del contenedor en línea debería mostrar el libro.
