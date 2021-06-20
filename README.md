# hello-world
Creación de un hello world utilizando tecnologias web.

El proyecto inicial consistía en crear un 'hola mundo', utilizando html5, javascript, algo de 3D (todavia no esta definido este punto, estoy estudiando utilizar armory3D o tecnologias similares, en todo caso utilizando Blender 3D) y algo de música, creada con ayuda del programa open-source 'Ardour'.

 Como contenido adyacente, tal vez hacer una enumeración de 'buenas practicas' en cuanto a diseño web, desde un punto de vista mas personal que académico, una especie de editorial u opinión sobre este asunto.

cambios recientes:
-Se ha implementado Compass SASS para la generación de hojas de estilo. Si no se deseea implementar, se pueden utilizar solamente las hojas de estilo ya generadas, que estan en el directorio 'cdd'. En caso de querer implementarse, sigue las instrucciones de este sitio:

http://compass-style.org/install/

Aquí tienes instrucciones de instalación y tutoriales básicos, por si no conoces esta tecnologia. Las plantillas SASS que utiliza Compass están en el directorio SASS, así como la plantilla de configuración de proyectos Compass, se encuentra en el directorio base (config.rb).

-Se ha añadido también una hoja de estilos responsive, con una plantilla base (responsive.scss y responsive.css) con opción ya preparada para adaptar a resoluciones desde 1300px de ancho a 250px.

Instrucciones de publicación.

En el caso de querer publicar el proyecto en un servidor, sólo has de subir los siguientes archivos

DIRECTORIO principal
 hola-mundo.html
devolver-saludo.js

Se ha de crear un directorio dentro del principal llamado css, y meter en este las hojas de estilo generadas por Compass, o diseñadas con otro sistema en el caso de no implementar compass sass.

Crear tambien un directorio llamado 'fuentes', y alojar en este la fuente llamada angrybirds-regular.ttf. 

Tanto la carpeta sass como el archivo config.rb no se deben subir a producción, son para utilizar en un servidor local y en un sistema que tenga instalado Compass SASS (http://compass-style.org).
