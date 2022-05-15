# HTMLyCSS_Platzi
Curso Definitivode HTML y CSS en Platzi
https://platzi.com/cursos/html-css/

Para comentarios usamos ctrl+/
Etiquetas para manejo de:

Imagenes: Mostrar imagenes, src para la root, direccion o url
-Debemos comprimir la Img para que el peso sea menor y renderize mas rapido en el website
<Img> nos permite colocar solo una imagen
        1-Art src: Root, url de donde esta la img
<Figure> nos permite colocar varias imagener 
        Podemos agregarle descripcion a la img
        con una etiqueta extra (<figcaption>)
        -Atributo alt para una pequena descripcion
        en caso no se pueda mostrar la img
        -figcaption: desc similar a la de alt pero
          que pueda ayudar a dar explicacion de que es la imagen
Tipos de Imagenes: 
        -Lossy:(Con perdida)Formato con un poco de perdida de calidad, 
        mejorando la carga mas rapida en el navegador
           -jpg jpeg gama de colores ilimitadas 
        -Lossless:(Sin perdida)Formatos sin perdida, misma calidad, imagenes pesadas
           -gif png  (fondo transparente) 256 colores
           -SVG vector ligero usado para logotipos 
        -Retirar metadatos de tus imagenes
        Metadatos son(fechas de toma de foto, location...)
        -Verexif 

Videos: Muestra videos, atrributo src para url, direc o root 
        1-atriburo controls, sin valor, para el manejo del
        video, play pause etc
        2-atributo preload = "auto", para que el navegador carge el video 
        antes de entrar a la pagina
        3-#t= seg inicio, seg final: funciona para 
        que el video empieze y termine en estos segundos respectivamente
Etiqueta <Source>: para poner videos de diferentes 
        formatos y se pone el src del video.

Formularios: --------
        Etiqueta <Forms>:Le dice al navegador que 
        viene un formulario y que el user dejara informacion que tendriamos que enviar al server
        Etiqueta <label>: Atributo for, es como un identificador de lo que se introduce en el form
        Etiqueta <input>: Atributo type para el manejo de informacion, recoleccion de info de distintos tipos
               1-Atributo id para identificarlo, debe ser igual al for de etiq label.
               2-Atributo name sirve para mandar la info,debe ser el mismo que for y e id
               3-Atributo type submit para enviar info
               4-Atrb autocomplete: el navegador nos ayuda con la respuesta que el usuario siempre pone, para ahorrar tiempo la autocompleta 
               5-Atrb required: Se utiliza para que el user llene los campos que son necesarios (Requeridos)
        Etiqueta <span>: Para agregar texto como descripcion, al lado de la box del form
        Atributo placeholder: Texto de ejemplo que le dice a la persona que info debe ir alli.
Existen dos maneras de crear una lista con distintas opciones.
        La primera es con Etiq <select> permite crear la lista con etiq de <option>
        (Usada para lista con pocas opciones)
        Etiqueta <select>: Sirve para hacer una lista de las opciones de input en un form.
        -Name: es el contenido en relacion a las options
        -Id:
        Etiq <Option> dentro de <select>: Opcion de cada input en la lista a seleccionar

        La segunda es con etiq <input list="  ">
        (Usada para muchas opciones)
        Etiq <datalist>: Permite al user escribir en el input y filtrar su resultado. 
        -Id sera igual al valor que tiene list.
        Etiq <Option> dentro de <datalist>: Opcion de cada input en la lista a seleccionar

Existen dos tipos de botones
        1-Etiq Input type="submit": Por defecto, muestra enviar o submit pero podemos cambiarlo
        con el atrb value="texto a mostrar" 
        (Utilizado en forms para enviar informacion)

        2-Etiq Button: Usado en acciones que no correspondan a "enviar" en un forms
        Muestra el texto entre etiqueta, le podemos poner el 
        atributo type="submit" para usarla en los formularios para que funcione como input 
        (Utilizado en cualquier caso que necesitemos un boton)


CSS  Cascading Style Sheets 