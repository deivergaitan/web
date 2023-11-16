<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
    <link rel="stylesheet" href="estilos2.css">
</head>
<body>
   
   <div class="head">

     

      <nav class=" logo">
         <a hreft="#"> Deiver-Gaitán</a>
         </nav>

       <nav class="navbar">
         <a href="#Definición">Definición</a>
         <a href="#Editor">Editor</a>
         <a href="#Estructura">Estructura</a>
         <a href="#Etiquetas">Etiquetas</a>
         <a href="#Listas">Listas</a>
         <a href="#Tablas">Tablas</a>
         <a href="#Cajas">Cajas</a>
         <a href="#DIV">DIV</a>
         <a href="#Enlace">Enlace</a>
 
       </nav>

   </div>
  
   <header class="content header " >
      <div class="item" id="Definición">
     <h2 class="title">Definición de HTML </h2>
      </div>
      <p>
           HTML un lenguaje de marcado que se utiliza para el desarrollo de páginas de Internet. Se trata de la sigla que corresponde a HyperText Markup Language, es decir, Lenguaje de Marcas de Hipertexto, que podría ser traducido como Lenguaje de Formato de Documentos para Hipertexto.
      </p>
      
   </header>
   
   <section class=" content sau">

      <h2 class=" title"> ¿Qué es HTML?</h2>
      
     <div>
         <img src = "html-1.png" width=" 400" alt="" />
     </div>
         <br>
         <p>
         Para entender "HTML" al derecho y al revés, veamos cada letra de esta contracción: 
      <br>
      </p>
      <br>
      <div class="container">
         <ul>
            <li>Hypertext (hipertexto): texto (usualmente enlaces) que está organizado de manera que conecta elementos relacionados.</li>
               <br/>
              <li> Markup (marcado): Es una guía de estilo para representar elementos que son mostrados de forma visual en el navegador.</li>
              <br/>
             <li>Language (lenguaje):Un lenguaje que entiende una computadora y utiliza para interpretar comandos.</li>
          </ul>
      </div>

   </section>
    
   <section   class="content abouts">
      <div class="item" id="Editor">
                <h2 class="title ">¿Qué es un editor HTML?</h2>
      </div>
     <p>
      Un editor HTML es una herramienta que te permite crear y editar código HTML. Los editores de HTML suelen ser más sencillos y fáciles de usar, además de ofrecer funciones básicas como resaltado de sintaxis, autocompletado o validación.
       </p>
       <br>
   </section>  

    <section class="content about">
           
         <h3 class=" title3">Mejores editores HTML</h3>
      
   <div class="container">  
      <ol>
      <li> Visual Studio Code</li>
      <ul>
        <li>Compatible con una amplia gama de lenguajes de programación.</li>
        <li>Ofrece una gran cantidad de extensiones para agregar funcionalidades. </li>
        <li> La funcionalidad IntelliSense te permite obtener sugerencias de autocompletado en base a los tipos de variables, funciones, etc.</li>
        <li> Compatible con Git.</li>
    
      </ul>
      <br/>
     <li>Atom </li>
     <ul>
        <li>Package manager instalado por defecto (+ 6.000 modificaciones disponibles).</li>
        <li>Integración completa con GitHub.</li>
        <li>Puedes trabajar con múltiples ventanas a la vez.</li>
        <li>El paquete Teletype te permite trabajar con tu equipo en tiempo real.</li>
    
     </ul>
     <br/>
     <li> Sublime text</li>
     <ul>
        <li>Multitud de atajos de teclado que agilizan el trabajo.</li>
        <li>Sistema de pantallas múltiples que permite trabajar con varios documentos a la vez.
        <li>Cuenta con numerosos plugins.</li>
        <li>Su resultado de sintaxis es uno de los mejores del mercado.</li>
        <li>Consume pocos recursos.</li>
     </ul>
     </ol>
   </div>

    </section>


    <section  class="content price">
      <div class="item" id="Estructura">
         <h2 class="title ">Estructura de una página web</h2>
      </div>
         <p>
           En la estructura de una página web tenemos tres partes diferenciadas: cabecera, cuerpo y pie de página. O, por sus términos en inglés: header, body y footer.
         </p>

         <h3 class=" title3">Cabecera o header</h3>
         <p>
            La cabecera es la parte superior de la página web. Aquí suele incluirse la información básica de la empresa o marca y es consistente en todo el sitio, es decir, se repite en cada página de la web por la que navegas.
         </p>
       
         <h4 class="title4">Los elementos que se incluyen en la cabecera son:</h4>
         <div class="container">
         <ul>
            <li>Logo de la empresa</li>
            <li>El menú de navegación</li>
            <li>Un cuadro de búsqueda</li>
            <li>una pequeña descripción de la web</li>
         </ul>
         </div>
         <p>
            Estos elementos muchas veces difieren en función de la plantilla de WordPress que utilices, pero son los más comunes. Si hablamos en lenguaje HTML, verás que todo el contenido de la cabecera aparece entre las siguientes etiquetas:
            <br>
            <br>
           Nota: Cuando creas una página web, es recomendable fijar la cabecera. ¿Qué quiere decir esto? Pues que a medida que un usuario hace scroll y navega a través de tu sitio, la cabecera se mantenga fija y tu marca y los accesos más importantes de tu página, como el menú, estén siempre visibles y accesibles.
         
         </p>

         <h3 class=" title3">Pie de página o footer</h3>
         <p>
            El pie de página o footer es la parte inferior de una página web. Al igual que la cabecera, se repite y es consistente en cada página. 
         </p>
           <h4 class="title4">En el footer podemos encontrar los siguientes elementos:</h4>
         
       <div class="container">
           <ul>
            <li>Menú simplificado</li>
            <li>Información de contacto</li>
            <li> Botones de redes sociales</li>
            <li>Logo de la empresa</li>
            <li>Enlace a la política de privacidad</li>
         
          </ul>
       </div>

   </section>  

   <section class="content bas">
      <div class="item" id="Etiquetas">
      <h2 class="title"> Etiquetas</h2>
      </div>
<p>
    Las <strong>etiquetas HTML</strong> son el lenguaje utilizado para estructurar y definir el contenido en un documento HTML. Estas etiquetas se encuentran en el HTML (o Lenguaje de Marcado de Hipertexto) de cada página. 
  <br/>
  <br/>
 Cada etiqueta contiene instrucciones sencillas que indican al navegador cómo dar formato al texto y a definir los diversos elementos de la página web. Al aplicar estas etiquetas de marcado a los diferentes elementos del texto, se indica al navegador cómo mostrarlos al usuario, lo que permite crear páginas web estructuradas y con un diseño coherente.
  <br/>
 <h4 class="title4">Las etiquetas HTML más utilizadas son:</h4>

 <div class="container">
   <ul>
     <li> <"html">: Define el inicio y el final de la página web. </li> 
     <br/>
     <li> <"head">: Define la sección de encabezado de la página, donde se incluyen elementos como el título de la página, metaetiquetas, scripts, entre otros. </li>
     <br/>
     <li> <"title">: Define el titulo de la página web que aparece en la pestaña del navegador.</li> 
     <br/>
     <li> <"body">: Define la sección del cuerpo de la página web, donde se incluyen todos los elementos que se mostrarán en la página.</li>
     <br/>
     <li> <"h1"> a <"h6">: Define los encabezados o títulos de diferentes niveles de jerarquía en la página web. El uso de esta etiqueta formateará cualquier texto entre la etiqueta <"h"> de apertura y la etiqueta <"/h"> de cierre como un Título o subtítulo. Por ejemplo, en <"h">Etiqueta de encabezamiento<"/h2">, <"h2"> y <"/h2"> serían las etiquetas HTML y "Etiqueta de encabezamiento" es el elemento HTML, es decir, el encabezamiento de la página. </li>
     <br/>
     <li> <"a">: Define un enlace que el usuario puede hacer clic para ir a otra página web o a una sección diferente de la misma página.</li>
     <br/>
     <li> <"img">: Define una imagen que se mostrará en la página web.</li>
     <br/>
     <li> <"p"> Etiqueta de párrafo<"/p">: Define un párrafo de texto. Las etiquetas <"p"> y <"/p"> son etiquetas HTML y la "Etiqueta de párrafo" es el elemento HTML, es decir, el texto de la página. Esta etiqueta formatea cualquier texto entre la etiqueta <"p"> de apertura y la etiqueta <"/p"> de cierre como un párrafo estándar o texto de cuerpo principal.</li>
     <br/>
     <li> <"i">Etiqueta de cursiva<"/i">: Esta etiqueta formateará como cursiva cualquier texto entre la etiqueta de apertura <"i"> y la etiqueta de cierre <"/i">. Aquí, <"i"> y <"/i"> son las etiquetas HTML y "Etiqueta cursiva" es el elemento HTML (el texto de la página).</li>
     <br/>
     <li> <"u">Etiqueta de subrayado<"/u">: Esta etiqueta formateará cualquier texto entre la etiqueta <"u"> de apertura y la etiqueta <"/u"> de cierre como subrayado. Aquí, <"u"> y <"/u"> son las etiquetas HTML y "Etiqueta de subrayado" es el elemento HTML, es decir, el texto de la página. </li>
     <br/>
     <li> <"br/">: Esta etiqueta se utiliza para dejar un espacio entre líneas.</li>
     <br/>
     <li> <"hr/>: Esta etiqueta sirve para agregar una línea separadora.</li>
    
   </ul>
 </div>
</p>

   </section>

   <section class="content cas">
      <div class="item" id="Listas">
      <h2 class="title">Listas HTML</h2>
      </div>
      <p>
         Las listas en HTML nos permite crear conjuntos de elementos en forma de lista dentro de una página, todos los cuales irán precedidos, generalmente, por un guión o número.
      </p>
         <div class="container">
         <ul>
            <li>Listas ordenadas</li>
            <li>Listas desordenadas</li>
        </ul>
         </div>
      

      <h3 class="title3">Listas ordenadas</h3>
      
      <p>
         Las listas ordenadas en HTML son aquellas que nos muestran los elementos de la lista en orden. Para representar el orden tendremos los elementos numerados. Es decir, cada uno de los elementos irá precedido de un número o letra que establezca su orden.
       <br/>
      Las listas ordenadas en HTML se representan mediante el elemento OL.
      <"ol"> ... <"/ol">
      <br/>
      <br/>
      Cada uno de los elementos de la lista ordenada se representará mediante el elemento LI.
      <br/>
      <br/>
      <"ol">
      <br/>
        <"li">Elemento 1<"/li">
        <br/>
        <"li">Elemento 2</"li">
        <br/>
        ...
        <br/>
        <"li">Elemento N<"/li">
        <br/>
     <"/ol">
      <br/>
      <br/>
      Un ejemplo de lista ordenada sería el siguiente:
      <br/>
      <br/>
      <"ol">
      <br/>
        <"li">Julio<"/li">
        <br/>
        <"li">Carmen<"/li">
        <br/>
        <"li">Ignacio<"/li">
        <br/>
        <"li">Elena<"/li">
        <br/>      
        <"/ol">
        <br/>
        <br/>
      Que produciría el siguiente efecto:
      <div class="container">
        <ol>
            <li> Julio</li>
            <li>Carmen</li>
            <li>Ignacio</li>
            <li>Elena</li>

        </ol>
      </div>
</p>
        <h3 class="title3"> Listas desordenadas</h3>

        <p>
        Las listas desordenadas en HTML nos sirven para mostrar los elementos sin ningún tipo de orden, simplemente precedidos por una viñeta que puede ser un punto, un cuadrado,…
        <br/>
        <br/>
        Para definir una lista desordenada en HTML utilizamos el elemento ul.
        <br/>
        <br/>
        <"ul"> ... <"/ul">
        <br/>
        <br/>
        Para representar los elementos de la lista desordenada utilizamos el mismo elemento que con las listas ordenadas, es decir, el elemento li.
        <br/>
        <br/>
        <"ul">
             <br/>
            <"li">Elemento 1<"/li">
            <br/>
            <"li">Elemento 2<"/li">
            <br/>
            ...
            <br/>
            <"li">Elemento N<"/li">
            <br/>
        <"/ul">
        <br/>
        <br/>
        De esa forma podríamos tener el siguiente código HTML:
        <br/>
        <br/>
        <"ul">
         <br/>
            <"li">FC. Barcelona<"/li">
            <br/>
            <"li">Real Madrid<"/li">
            <br/>
            <"li">Real Betis<"/li">
            <"br">
            <"li">Atlético de Madrid<"/li">
            <br/>
          <"/ul">
          <br/>
          <br/>
          Lo que nos mostrará por pantalla:
          <br/>
          <div class="container">
          <ul>
            <li>FC. Barcelona</li>
            <li>Real Madrid</li>
            <li>Real Betis</li>
            <li>Atlético Madrid</li>
          </ul>
          </div>
      </p>

   </section>

   <section class="content das">
      <div class="item" id="Tablas">
      <h2 class="title">Tablas en HTML</h2>
      </div>
    <h3 class="title">Concepto</h3>
    <p>
        Una tabla no es otra cosa más que un medio de organizar datos en filas y columnas. Este concepto ha estado presente en nuestra sociedad por un largo período de tiempo y ha sido adoptado por HTML en sus etapas iniciales, como una forma de transmitir información que, de otro modo, no sería comprendida tan fácilmente.
        <br/>
        <br/>
        En documentos HTML una tabla puede ser considerada, resumidamente, como un grupo de filas donde cada una contiene a un grupo de celdas. Esto es conceptualmente distinto a un grupo de columnas que contiene a un grupo de filas, y esta diferencia tendrá un impacto en la composición y comportamiento de la tabla.
        <br/>
        <br/>
        Como muchas otras estructuras de HTML, las tablas son construidas utilizando elementos. En particular, una tabla básica puede ser declarada usando tres elementos, a saber, table (el contenedor principal), tr (representando a las filas contenedoras de las celdas) y td (representando a las celdas).
        <br>
        Dejémoslo más claro con un ejemplo:
        <br/>
        <br/>
        <"table class="default">
          <br/>
            <"tr">
             <br/>
              <"td">Celda 1<"/td">
             <br/>
              <"td">Celda 2</"td">
             <br/>
              <"td">Celda 3<"/td">
             <br/>
            <"/tr">
             <br/>
            <"tr">
             <br/>
              <"td">Celda 4<"/td">
             <br/>
              <"td">Celda 5<"/td">
             <br/>
              <"td">Celda 6<"/td">
             <br/>
            <"/tr">
             <br/>
       <"/table">
       <br/>
       <br/>
       Resultado:
       <br>
       <table class="default">

        <tr>
      
          <td>Celda 1</td>
      
          <td>Celda 2</td>
      
          <td>Celda 3</td>
      
        </tr>
      
        <tr>
      
          <td>Celda 4</td>
      
          <td>Celda 5</td>
      
          <td>Celda 6</td>
      
        </tr>
      
      </table>
      
      <br>
      <br>
      <h3 class="title3"> Celdas de encabezado</h3>
      <p>
        Una celda de encabezado es un tipo especial de celda utilizada para organizar y categorizar otras celdas en la tabla. Dicho esto, es diícil imaginar una tabla donde una celda de encabezado no tenga utilidad. Casi cualquier tabla puede beneficiarse de un grupo de celdas de encabezado bien ubicado.
         <br>
         <br>
         En el siguiente ejemplo, construiremos una tabla para mostrar información acerca del clima en los próximos días. Aquí, las celdas de encabezado, representadas por el elemento th, son ubicadas en la primera fila de la tabla, encima de las celdas comunes.
         <br/>
         <br/>
    </p>
      <p>
      <"table class="default">
      <br>
        <"tr">
      <br>
          <"th">Hoy<"/th">
      <br>
          <"th">Mañana<"/th">
      <br>
          <"th">Miércoles<"/th">
      <br>
        <"/tr">
      <br>
        <"tr">
      <br>
          <"td">Soleado<"/td">
      <br>
          <"td">Mayormente soleado<"/td">
      <br>
          <"td">Parcialmente nublado<"/td">
      <br>
        <"/tr">
      <br>
        <"tr">
      <br>
          <"td">19°C<"/td">
      <br>
          <"td">17°C<"/td">
      <br>
          <"td">12°C<"/td">
      <br>
        <"/tr">
      <br>
        <"tr">
      <br>
          <"td">E 13 km/h<"/td">
      <br>
          <"td">E 11 km/h<"/td">
      <br>
          <"td">S 16 km/h<"/td">
      <br>
        <"/tr">
      <br>
      <"/table">
      <br>
      <br>
      Resultado:
    </p>
      <br>
      <table class="default">
       <thead>
        <tr>
      
          <th>Hoy</th>
      
          <th>Mañana</th>
      
          <th>Miércoles</th>
      
        </tr>
       </thead>
        <tr>
      
          <td>Soleado</td>
      
          <td>Mayormente soleado</td>
      
          <td>Parcialmente nublado</td>
      
        </tr>
      
        <tr>
      
          <td>19°C</td>
      
          <td>17°C</td>
      
          <td>12°C</td>
      
        </tr>
      
        <tr>
      
          <td>E 13 km/h</td>
      
          <td>E 11 km/h</td>
      
          <td>S 16 km/h</td>
      
        </tr>
      
      </table>
    </p>
    <br>
    <br>

   </section>

   <section class="content caj">
      <div class="item" id="Cajas">
            <h2 class="title">Cajas HTML</h2>
      </div>
            <p>
               El modelo de cajas es la base del diseño web — cada elemento se representa como una caja rectangular, con su contenido, padding (espacio interior), borde y margen construidos uno sobre otro como las capas de una cebolla.
            </p>

   </section>

   <section class="content et">
      <div class="item" id="DIV">
             <h2 class="title">Etiquetas DIV</h2>
      </div>
             <p>
               Como se ha visto en las etiquetas previas, maquetar o estructurar una página web consiste en organizar su contenido para que cada elemento aparezca en el lugar y con el formato deseado. El formato (los estilos) se dejan para CSS y la estructura se organizamos en HTML.
            <br>
            <br>
            El código mostrado a continuación es un ejemplo de estructuración de una página mediante la etiqueta div, procedimiento empleado antes de la versión 5 de HTML.
            </p>

   </section>

   <section class="content enl">
      <div class="item" id="Enlace">
        <h2 class="title">Enlaces en HTML</h2>
      </div>
        <p>
         En el HTML los enlaces se marcan con la etiqueta <"a"><"/a"> y el atributo principal es href="" donde se escribe la ubicación del archivo de destino que puede estar en la misma carpeta que el archivo que lo está llamando, en otra carpeta del mismo sitio o en otro sitio web.
        <br>
        <br>
        Entre las etiquetas <"a href"=" "><"/a"> se puede colocar cualquier elemento html que funcionará como botón, generalmente se coloca un texto o una imagen. Si es un texto, el navegador por defecto lo muestra en color azul y subrayado.
      </p>

   </section>
    

 </body>
</html>
