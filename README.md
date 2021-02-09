# Actividad 04. Formas y Tablas en HTML5

## Pasos a seguir

1. Clone su repositorio asignado usando **git clone** en la carpeta donde usted desee

2. Modifique el contenido del repositorio de acuerdo a lo indicado en la sección de Instrucciones

3. Conforme vaya realizando cambios, registre tales cambios de manera atómica usando **git add** y **git commit**. Recuerde que un commit es atómico si solo incluye el archivo donde se hizo el cambio y no incluye en el mismo commit varias modificaciones. Al hacer los commit especifique un mensaje breve que deje claro el trabajo realizado.

4. Al final, haga push de sus cambios al repositorio remoto usando **git push**. Si desea, puede estar haciendo push esporádicamente aunque no haya finalizado su trabajo para mantener una copia de su trabajo en el repositorio remoto.

## Instrucciones

Para esta actividad, debe escribir en el archivo **catalogopeliculas.html** proporcionado, las etiquetas necesarias para crear una forma y una tabla para que se vean como en la siguiente figura al abrir la página en un navegador:

![Jerarquia de Paginas](https://github.com/rsolisuaz/act04_desappint_ej2021/blob/master/imagenes/imagenactividad04.png)

1. El archivo **catalogopeliculas.html** deberá contener lo siguiente:
   - Un encabezado **h1** con el texto `Catálogo de Películas de NNNNNNN` donde NNNNNNN se sustituye por su nombre completo
   - El contenido de la etiqueta title en la sección head debe contener lo mismo que la etiqueta **h1**
   - Un div de clase formadatos que deberá contener los siguientes elementos:
     + Un input type de tipo text y de nombre e id **titulo** para contener el titulo de la pelicula, deberá tener como atributo placeholder el valor `Teclea titulo de la película` y como etiqueta *Titulo:*
     + Un input type de tipo number, de nombre e id **year**, para contener el año de producción (valores posibles en el rango del 1900 a 2021, con un valor default de 1980) y como etiqueta *Año de Producción:*
     + Un par de radio buttons de nombre **traduccion** con los valores **S** y **D** respectivamente, con los texto **Subtitulada** y **Doblada** respectivamente, y como etiqueta *Tipo de Traducción:*. El primer radio button tendrá como id **traduccion1**
     + Un select de nombre e id **productora** que tenga como etiqueta *Productora* con las siguientes opciones (valor, texto):
       - (P,Paramount Pictures)
       - (U,Universal Pictures)
       - (W,Warner Brothers)
       - (S, Sony Pictures)
       - (O,Otra)
     + Un conjunto de checkbox de nombre **genero**, con etiqueta *Género:* y con los siguientes valores y textos (el primero de ellos tendrá id **genero1**:
       - A,Acción
       - D,Drama
       - C,Comedia
       - S,Suspenso
       - F,Ciencia Ficción
       - M,Animada
     + Un textarea de nombre e id **sinopsis** de 8 renglones por 80 columnas con la etiqueta *Sinopsis de la película:*
     + Un botón para limpiar el contenido con el valor **Borrar**
     + Un botón para enviar el contenido con el valor **Enviar**
   - Un div de clase listado que contendrá una tabla con id **listadopeliculas** que contendrá una línea de encabezado (creada con un thead y un tr) y un contenido (creada con un tbody de id **contenidotabla** y por lo menos 4 renglones). Estos renglones contendrán 6 columnas como se muestra en la figura, el encabezado debe tener el texto que se muestra en la figura, los 4 renglones de contenido pueden contener la información de las películas que usted desee.
   - La página debe ser validada usando https://validator.w3.org/

2. El archivo debe contener su nombre y matrícula como comentario (sustituir la línea 2)

