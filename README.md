# HTMLyCSS_Platzi
Curso Definitivode HTML y CSS en Platzi
https://platzi.com/cursos/html-css/

Para comentarios usamos ctrl+/
Etiquetas para manejo de:

-Debemos comprimir la Img para que el peso sea menor y renderize mas rapido en el website
Imagenes: Mostrar imagenes, src para la root, direccion o url
Img nos permite colocar solo una imagen
Figure nos permite colocar varias imagener 
        Podemos agregarle descripcion a la img
        con una etiqueta extra (figcaption)
        -Atributo alt para una pequena descripcion
        en caso no se pueda mostrar la img
        -figcaption: desc similar a la de alt pero
          que pueda ayudar a dar explicacion de que es la imagen
Tipos de Imagenes: 
        -Lossy:(Con perdida)
        -Lossless:(Sin perdida)


Videos: Muestra videos, 
        1-atriburo controls, sin valor, para el manejo del
        video, play pause etc
        2-atributo preload = "auto", para que el navegador carge el video 
        antes de entrar a la pagina
        3-#t= seg inicio, seg final: funciona para 
        que el video empieze y termine en estos segundos respectivamente
Etiqueta Source: para poner videos de diferentes 
        formatos y se pone el src del video.

Formularios: --------
        Etiqueta Forms:Le dice al navegador que 
        viene un formulario y que el user dejara informacion que tendriamos que enviar al server
        Etiqueta label: Atributo for, es como un identificador de lo que se introduce en el form
        Etiqueta input: Atributo type para el manejo de informacion, recoleccion de info de distintos tipos
               1-Atributo id para identificarlo, debe ser igual al for de etiq label.
               2-Atributo name sirve para mandar la info,debe ser el mismo que for y e id
               3-Atributo type submit para enviar info
               4-Atrb autocomplete: el navegador nos ayuda con la respuesta que el usuario siempre pone, para ahorrar tiempo la autocompleta 
               5-Atrb required: Se utiliza para que el user llene los campos que son necesarios (Requeridos)
        Etiqueta span: Para agregar texto como descripcion, al lado de la box del form
        Atributo placeholder: Texto de ejemplo que le dice a la persona que info debe ir alli.