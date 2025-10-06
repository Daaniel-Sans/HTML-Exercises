**Primero se abre el formulario con la etiqueta <form>** 

En la etiqueta de apertura especificamos con "action" a dónde se envían los datos. Como no queremos enviarlos a ningún sitio usamos ="#"

Con method establecemos la manera de enviarlos, ya sea haciéndolos visibles en la barra de búsqueda (get) o escondiéndolos en el cuerpo de la petición como en este caso (post), lo cual es más seguro.

De este modo la etiqueta de apertura quedaría así 

    <form action="#" method="post">

El elemento **input type="text"** define una sola línea de texto para el campo de texto.

Con **label** definimos el area de acción de los imputs y asociamos los textos con los campos. El atributo **"for"** hará referencia al id de un campo de entrada de datos, relacionándolo aunque la etiqueta <label> no incluya el campo de entrada de datos, permitiéndonos separarlo por si el aspecto visual o estético lo requiere.

-**br** sirve para dar un salto de línea sin crear un párrafo  
    
-**maxlength="30"** establece el límite de caracteres de un campo (es un atributo)

La etiqueta **label** con todas estas especificaciones quedaría así: 

    <label for="nombre">Nombre:</label><br>

**required** es un atributo que establece la obligatoriedad para rellenar un campo antes de enviar los datos

**select** Define un menú desplegable o cajetín para que el usuario seleccione una opción de varias.

Sus atributos más comunes:

    id="asunto" → identifica el elemento en HTML o CSS.

    name="asunto" → el nombre que se envía al servidor cuando se envía el formulario.

    size="3" → indica cuántas opciones se muestran al mismo tiempo; si pones 3, se ve un cajetín con 3 filas visibles, no un menú desplegable típico.

Cada **option** es una opción dentro del **select**.

Atributos:

    value="presupuesto" → el valor que se envía al servidor si el usuario selecciona esa opción.

El texto entre las etiquetas **option** → es lo que ve el usuario en la lista.