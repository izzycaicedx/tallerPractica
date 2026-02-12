# tallerPractica
1.	¿Qué es HTML y cuál es su función en la web?

R// Es u  lenguaje estándar que se utiliza para crear y estructurar paginas web mediante etiquetas y elementos que permiten incluir textos, imágenes, enlaces, videos 

2.	¿Que es una etiqueta HTML y menciona las etiquetas más comunes?

R// Son códigos utilizados para "marcar" el texto de una página web, con el fin de dar instrucciones al navegador sobre cómo mostrarlo.

Cada etiqueta contiene instrucciones sencillas que indican al navegador cómo dar formato al texto y a definir los diversos elementos de la página web. Al aplicar estas etiquetas de marcado a los diferentes elementos del texto, se indica al navegador cómo mostrarlos al usuario, lo que permite crear páginas web estructuradas y con un diseño coherente.

etiquetas más comunes

•	<!DOCTYPE>: Se utiliza para especificar la versión de HTML que se está utilizando en la página.

•	<html>: Define el inicio y el final de la página web.

•	<head>: Define la sección de encabezado de la página, donde se incluyen elementos como el título de la página, metaetiquetas, scripts, entre otros.

•	<title>: Define el título de la página web que aparece en la pestaña del navegador.

•	<body>: Define la sección del cuerpo de la página web, donde se incluyen todos los elementos que se mostrarán en la página.

•	<h1> a <h6>: Define los encabezados o títulos de diferentes niveles de jerarquía en la página web.
•	<a>: Define un enlace que el usuario puede hacer clic para ir a otra página web o a una sección diferente de la misma página.

•	<img>: Define una imagen que se mostrará en la página web.

•	<p>Etiqueta de párrafo</p>: Define un párrafo de texto

•	<b>Etiqueta de negrita</b>: Esta etiqueta dará formato de negrita a cualquier texto que se encuentre entre la etiqueta <b> de apertura y la etiqueta </b> de cierre.

•	<i>Etiqueta de cursiva</i>: las etiquetas HTML y "Etiqueta cursiva" es el elemento HTML (el texto de la página).

•	<u>Etiqueta de subrayado</u>:son las etiquetas HTML y "Etiqueta de subrayado" es el elemento 

3.	¿Que es un atributo de una etiqueta HTML y menciona los más comunes?

R// Un atributo es información adicional que se coloca dentro de la etiqueta de apertura para modificar su comportamiento o apariencia. Siempre siguen la estructura: nombre="valor".

Regla de oro: El atributo siempre va en la etiqueta de inicio, nunca en la de cierre

Atributos comunes:

•	Id: Sirve para identificar de forma individual a cada elemento HTML.	id="ejemplo"
•	Class: Permite asignar un elemento a una o varias clases.	class="coches"
•	Style: Define el estilo de un elemento HTML y puede determinar, por ejemplo, su color, fuente o tamaño.	style="color: blue; font-size: 2em"
•	Title: Contiene información adicional sobre el contenido de un elemento; se muestra, por ejemplo, en una ventana separada cuando se pasa el ratón por encima del elemento en cuestión.	title="texto de ejemplo"
•	Lang: Establece el idioma base de un documento.	<html lang="es">
•	Dir: Define el sentido de lectura de un texto, bien sea de izquierda a derecha o viceversa.       <html dir="ltr">ejemplo</html>
4.	¿Qué es CSS y cómo se utiliza para el diseño web?

R// Es el lenguaje que le dice al navegador exactamente cómo debe verse el contenido: de qué color es el texto, qué tamaño tienen las imágenes, cuánto espacio hay entre los párrafos y cómo se deben organizar los elementos en la pantalla

Ejemplo de como se utiliza: 

1.	El HTML (La estructura)
Primero, creamos el elemento. En este caso, un enlace que queremos que parezca un botón:

HTML
<a href="#" class="mi-boton">¡Haz clic aquí!</a>

2. El CSS (El diseño)
Aquí es donde aplicamos lo que aprendimos (colores, cajas y bordes):

CSS
.mi-boton {
  background-color: #3498db; /* Color azul */
  color: white;              /* Texto blanco */
  padding: 15px 30px;        /* Espacio interno (arriba/abajo y lados) */
  text-decoration: none;     /* Quita el subrayado típico de los enlaces */
  border-radius: 8px;        /* Redondea las esquinas */
  font-family: Arial;        /* Cambia el tipo de letra */
  display: inline-block;     /* Permite que el botón tenga cuerpo */
}
background-color: #2980b9; /* Un azul más oscuro */
}
5.	¿Que es una propiedad en CSS y menciona las propiedades más comunes?

R// Una propiedad es un aspecto específico de un elemento HTML que puedes modificar. En el código, la propiedad siempre va antes de los dos puntos (:) y define qué quieres cambiar.

Propiedades más comunes

Las propiedades se dividen según lo que controlan. Aquí tienes las fundamentales que usarás siempre:

1. Para el Texto
color: Cambia el color de la letra (ej. red, #000000).
font-size: Controla el tamaño de la letra (ej. 16px, 2rem).
font-family: Define el tipo de fuente (ej. Arial, 'Open Sans').
text-align: Alinea el texto (ej. center, left, justify).

2. Para el Fondo y Bordes
background-color: Cambia el color de fondo de un elemento.
background-image: Permite poner una imagen detrás del contenido.
border: Define el grosor, estilo y color de un borde (ej. 2px solid black).
border-radius: Redondea las esquinas (para hacer botones circulares o suavizados).

3. Para el Espaciado (Modelo de Caja)
width / height: El ancho y el alto del elemento.
padding: El espacio dentro del elemento (entre el borde y el texto).
margin: El espacio fuera del elemento (para separarlo de otros).

4. Para el Diseño (Layout)
display: Define cómo se comporta el elemento (ej. flex para diseños modernos o none para ocultarlo).
opacity: Controla la transparencia (de 0 a 1).

6.	¿Que es un selector en CSS y cuales tipos existen?

R// El selector es el "puntero" que le dice al navegador: "A este elemento específico es al que quiero aplicarle el diseño".

•	Selector de Etiqueta: Afecta a todos los elementos con ese nombre (ej: p, h1, div).
•	Selector de Clase: Usa un punto . seguido del nombre. Se usa para aplicar el mismo estilo a varios elementos (ej: .boton-azul).
•	Selector de ID: Usa un hashtag #. Es único y solo debe aplicarse a un elemento en toda la página (ej: #menu-principal).
•	Selector Universal: El asterisco * afecta a absolutamente todos los elementos de la web.


7.	¿Qué es JavaScript y cómo añade la interactividad a las páginas web?

R// JavaScript añade funcionalidad y comportamiento a las páginas web. Puede responder a las acciones del usuario, manipular contenido, validar formularios, gestionar eventos y más.


8.	¿Cuáles son los tipos de datos primitivos en Javascript?

R// Son los valores más básicos que el lenguaje puede manejar:

•	String: Texto (ej: "Hola Mundo").
•	Number: Números, tanto enteros como decimales (ej: 25 o 3.14).
•	Boolean: Valores lógicos (true o false).
•	Undefined: Una variable que ha sido declarada pero no tiene valor.
•	Null: Representa la ausencia intencional de valor.
•	Symbol y BigInt: Para casos más avanzados y números muy grandes.


9.	¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript?

R// Deciden qué camino toma el código dependiendo de las condiciones:

•	if / else: Es un "Si pasa esto, haz aquello; si no, haz esto otro".
•	switch: Útil cuando tienes muchas opciones posibles para una sola variable (como un menú de opciones).
•	Bucles (for, while): Sirven para repetir una tarea muchas veces sin escribir el código una y otra vez.


10.	¿Por qué es importante usar nombres significativos para variables y métodos?

R// Es vital porque el código se lee más veces de las que se escribe.
•	Mal nombre: let x = 10; (¿Qué es x?).
•	Buen nombre: let edadUsuario = 10; (Cualquiera entiende qué guarda). Esto evita errores, facilita el trabajo en equipo y ayuda a tu "yo del futuro" a entender qué hiciste hace seis mese


11.	¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general?

R//  Una variable de entorno es un valor dinámico que se almacena en el sistema operativo o en el servidor donde se ejecuta tu código, en lugar de estar escrito directamente en el código fuente.

12.	¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?

R//  Son un conjunto de utilidades creadas para programadores que vienen integradas en el navegador. Permiten ver "detrás de escena" de cualquier web para editar el código, arreglar errores y medir el rendimiento.
•	Cómo acceder:
o	Presionando la tecla F12.
o	Con el atajo Ctrl + Shift + I (Windows) o Cmd + Opt + I (Mac).
o	Haciendo clic derecho en cualquier parte de la página y seleccionando "Inspeccionar".


13.	¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?

R// Es el lugar para trabajar con la estructura y el diseño. En este panel puedes:
•	Modificar el HTML: Puedes cambiar textos, borrar botones o mover elementos de lugar para ver cómo queda la página sin riesgo (los cambios desaparecen al recargar).
•	Editar el CSS: Puedes activar/desactivar colores, cambiar tamaños de fuente o ver qué reglas de estilo están chocando entre sí.
•	Inspeccionar el "Box Model": Ver gráficamente el margen, borde y relleno (padding) de cada elemento.
 
14.	¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?

R// La consola funciona como una línea de comandos o un "chat" directo con el motor de JavaScript de la página.

•	Para qué es útil:
o	Ver errores: Si un script falla, la consola te dirá exactamente en qué línea está el error.
o	Interactuar con el código: Puedes escribir funciones o variables y ejecutarlas al instante.
o	Depuración (Debugging): Los programadores usan console.log() para imprimir mensajes y verificar qué está pasando dentro de sus programas.


15.	¿Qué información se puede obtener del panel "Network" y por qué es importante?

R// Este panel registra todas las peticiones que hace el navegador al servidor.
•	Información que obtienes:
o	Lista de todos los archivos cargados (imágenes, scripts, fuentes).
o	Estado de la petición: Si el archivo cargó bien (Código 200) o si no se encontró (Error 404).
o	Tiempo de carga: Cuántos milisegundos tarda cada recurso en bajar.
•	Por qué es importante: Es vital para la optimización. Si una página es lenta, el panel Network te mostrará qué imagen es demasiado pesada o qué script está bloqueando la carga, permitiéndote mejorar la velocidad de la web.














HTML, es decir, el texto de la página.
