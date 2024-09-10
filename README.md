<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manual de HTML</title>
    
</head>
<!DOCTYPE html>
<html lang="es">
<body style="background-color: lightgrey;>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú de Navegación</title>
    <style>
        /* Estilo básico para el menú de navegación */
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            background-color: #333;
        }
        nav ul li {
            display: inline;
            padding: 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        nav ul li a:hover {
            background-color: #111;
        }
    </style>
</head>
<body>

   <center> <h1>Menú de Navegación</h1>
    <nav>
        <ul>
           
            <li><a href="#Codigos">Etiquetas basicas</a></li>
            <li><a href="p2.html">Formulario (pag.2)</a></li>
            <li><a href="p3.html">Etiquetas audiovisuales y vinculos (pag.3)</a></li>
        </ul>
    </nav></center>

    <section id="Codigos">
       
        <center>
     
    <div style="background-color: #66656a; padding: 10px;"><h2><u style="color: white;">Tamaños de encabezados:</u></h2></div>
    <h3>Puedes modificar el tamaño de tus encabezados usando;</h3>
    <h1>"h1"; Tipo 1</h1>
    <h2>"h2"; Tipo Nivel 2</h2>
    <h3>2h3"; Tipo Nivel 3</h3>

    <div style="background-color: #66656a; padding: 10px;"><h2><u style="color: white;">Tipos de arreglos en textos:</u></h2></div><h3>Existen distintas formas de perzonalizar tus textos, aquí unos ejemplos;</h3>
    <font size="4"> 
<p>con "p" puedes agrupar parrafos. Los párrafos son útiles para agrupar texto </p>
    <p><u>con la etiqueta "u" puedes subrayar textos</u></p>
    <p>con la etiqueta "b" puedes destacar textos en <b>negritas</b></p>
    <p>con la etiqueta "strong" puedes destacar textos en <strong>negrita fuerte</strong>.</p>
    <p>con la etiqueta "i" puedes escribir textos y palabras en <i>cursiva</i></p>
    <p>con "em" puedes hacer <em>enfasis</em> en las palabras</p></font>


   <div style="background-color: #66656a; padding: 10px;"> <h2 style="color: white;"><u> Tamaño del Texto</u></h2></div>
    <h3>Modifica el tamaño del texto desde el apartado css o con la etiqueta style "font-size";</h3>
    <style>
        .pequeno {
            font-size: 12px;
        }
        .mediano {
            font-size: 20px;
        }
        .grande {
            font-size: 30px;
        }
    </style>
    <p class="pequeno">Este es un texto pequeño.</p>
    <p class="mediano">Este es un texto mediano.</p>
    <p class="grande">Este es un texto grande.</p>



    <div style="background-color: #66656a; padding: 10px;"><h2 ><u style="color: white;">Alineación del Texto</u></h2></div>
    <h3>Usa la propiedad text-align para alinear el texto;</h3>
    <style>
        .izquierda {
            text-align: left;
        }
        .centro {
            text-align: center;
        }
        .derecha {
            text-align: right;
        }
    </style>
</head>
<body>
    
    <p class="izquierda">Este texto está alineado a la izquierda.</p>
    <p class="centro">Este texto está alineado al centro.</p>
    <p class="derecha">Este texto está alineado a la derecha.</p>

</center>

   
 <div style="background-color: #66656a; padding: 10px;"><h2><u style="color: white;" >Tipos de listas:</u></h2></div>
    <font size="4">
        <u><h3>Para las listas NO ordenadas debes utilizar la etiqueta "ul" para crear la tabla y "li" para hacer la lista</h3></u>
        

    </font>
    <h3>Lista No Ordenada</h3>
    <ul>
        <li>queso</li>
        <li>papas</li>
        <li>pan</li>
    </ul>

    <font size="4">
        <u><h3>Para la lista ordenada utiliza "ol" para crear la tabla y "li" ennumerara la lista</h3></u>
        

    </font>
    <h3>Lista Ordenada</h3>
    <ol>
        <li>pedro</li>
        <li>luis</li>
        <li>pepe</li>
    </ol>

   <font size="4">
        <u><h3>Para crear una tabla de registro utiliza "tr" y "th" para agregar contenido a la tabla</h3></u>
        

    </font>
    <h3>Tabla de Ejemplo</h3>
    <table border="1">
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
            <th>Ciudad</th>
        </tr>
        <tr>
            <td>Juan</td>
            <td>30</td>
            <td>Madrid</td>
        </tr>
        <tr>
            <td>María</td>
            <td>25</td>
            <td>Barcelona</td>
        </tr>
    </table>
    
    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Div y Span</title>
</head>
<body>

   
    <div style="background-color: #66656a; padding: 10px;">
        <center><h3 style= "color: white;">Este es un div que actúa como un contenedor de bloque.</h3>
        <h3 style= "color: white;">Dentro puedes agregar distintos elementos. Puedes usar esta funcion con la etiqueta "div"</h3></center>
    </div>

    
   <center> <p><h3>Ejemplo de <span style="color: red;">span</span> dentro de un párrafo.</h3></p><h3> Sirve para destacar palabras o textos esteticamente. puedes usar la etiqueta "span style"</h3></center>

  
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>

<body>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">





</body>
</html>
