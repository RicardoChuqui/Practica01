# Pagina Web la tecnologia en la Actualidad

Estructurar un sitio web estático usando HTML5. El sitio web será informativo sobre un tema que será autoría del estudiante. El sitio web deberá contar con una página principal denominada index.html y debe contener al menos cinco páginas *.html más. Todas las páginas contaran con un menú de navegación que permitirá al usuario moverse entre todas las páginas HTML. 

## Definición y uso de las etiquetas usadas
El elemento "header" representa un contenedor para contenido introductorio o un conjunto de enlaces de navegación.

Un elemento "header" típicamente contiene:

-uno o más elementos de encabezado h1 y h6

-logo o icono

-información de autoría

### Definición y uso de la etiqueta 
    
La etiqueta "nav" define un conjunto de enlaces de navegación.

Observe que NO todos los enlaces de un documento deben estar dentro de un elemento. El elemento está destinado solo para el bloque principal de enlaces de navegación.

### Definición y uso de la etiqueta 
    
El elemento "footer" representa al pie de una sección o documento, donde los autores habitualmente colocan firmas, información acerca del autor, información de licencias, documentos relacionados, etc.

### Definición y uso de la etiqueta 
La etiqueta "section" define las secciones de un documento, como capítulos, encabezados, pies de página o cualquier otra sección del documento.

### Definición y uso de la etiqueta 
La etiqueta "article" especifica contenido independiente y autocontenido.

Un artículo debería tener sentido por sí mismo y debería ser posible distribuirlo independientemente del resto del sitio.

Fuentes potenciales para el elemento "article":

-Mensaje del foro
-Entrada en el blog
-Noticia
-Comentario

### Definición y uso de la etiqueta
La etiqueta "aside" define un contenido aparte del contenido en el que se encuentra.

El contenido aparte debe estar relacionado con el contenido que lo rodea.

### Usando el atributo id
El id atributo especifica una identificación única para un elemento HTML (el valor debe ser único dentro del documento HTML).

El valor de id puede ser utilizado por CSS y JavaScript para realizar ciertas tareas para un elemento único con el valor de id especificado.


### Definición y uso de la etiqueta
El elemento HTML "iframe" (de inline frame) representa un contexto de navegación anidado, el cual permite incrustrar otra página HTML en la página actual como un enlace de video de youtube.

### Definición y uso de la etiqueta

Una tabla HTML se define con la "table" etiqueta.

Cada fila de la tabla se define con la "tr" etiqueta. Un encabezado de tabla se define con la "th" etiqueta. Por defecto, los encabezados de las tablas están en negrita y centrados. Una tabla de datos / celda se define con la "td" etiqueta.
  
## Ejecutando las pruebas ⚙️

b.	Los resultados fueron satisfactorios a continuación detallamos el mismo.

c.	Contamos con una vista principal de la página web desarrollada.

d.	La imagen central seria la página de entrada como visualización por parte del usuario.

e.	Las imágenes mas pequeñas y del mismo tamaño serian el menú en el que vamos a ingresar para     conocer mas a fondo sobre de que se trata la información detallada en las misma.

f.	Para poder ingresar y visualizar la información de las paginas vasta con darle un clic en       una de las imágenes.

c.	Continuamos con las demás paginas en este caso ingresamos a la de sociedad ya que también se     cuenta con un menú para poder navegar entre las diferentes páginas.
d.	En esta pagina también se cuanta con un video explicativo sobre el impacto de la tecnología     en la sociedad
e.	Para poder subir un video en una pagina HTML5 vasta con dirigirse a la pantalla del video       dar clic izquierdo y seleccionar Copiar código de inserción este código se le pega en la         página de HTML que queremos que se reproduzca un video. 

## Para mejorar la apariencia de la pagina web usamos CSS3
CSS3 es la última evolución del lenguaje de las Hojas de Estilo en Cascada (Cascading Style Sheets), y pretende ampliar la versión CSS2.1. Trae consigo muchas novedades altamente esperadas , como las esquinas redondeadas, sombras, gradientes , transiciones o animaciones, y nuevos layouts como multi-columnas, cajas flexibles o maquetas de diseño en cuadrícula (grid layouts).

## CSS3 Backgrounds and Borders
-Soporte en fondos para cualquier tipo de "image" y no solo las uri() definidas.
-Soporte para multiples imágenes de fondo.
-Los valores background-repeat space y round, y para la sintaxis de dos-valores de esta propiedad CSS.
-El valor local de background-attachment.
-Las propiedades CSS de background-origin, background-size y background-clip.
-Soporte para border curvos con las propiedades CSS border-radius, border-top-left-radius, border-top-right-radius, border-bottom-left-radius, y border-bottom-right-radius.
-Soporte para el uso de una "image" como borde con las propiedades CSS border-image, border-image-source, border-image-slice, border-image-width, border-image-outset, y border-image-repeat.
-Soporte para sombras de elemento con la propiedad CSS box-shadow.

## Propiedades de texto
La propiedad word-spacing define una cantidad adicional de espacio entre palabras. El valor debe estar en formato de longitud; no se permiten valores negativos.

Ejemplos:

P EM   { word-spacing: 0.4em }
P.nota { word-spacing: -0.2em }

La propiedad letter-spacing define una cantidad adicional de espacio entre caracteres. El valor debe estar en formato de longitud; no se permiten valores negativos. Un ajuste de 0 evitará justificación.

Ejemplos:

H1     { letter-spacing: 0.1em }
P.note { letter-spacing: -0.1em }

La propiedad text-decoration permite que el texto sea decorado mediante una de cinco propiedades: underline (subrayado), overline (línea superior), line-through (tachado), blink (parpadeo), o la por defecto none (ninguna).

Por ejemplo, uno puede sugerir que los enlaces no se subrayen con

A:link, A:visited, A:active { text-decoration: none }

La propiedad line-height aceptará un valor para controlar el espacio entre líneas base de texto. Si el valor es un número, la altura de línea se calcula multiplicando el tamaño de fuente del elemento por el número. Los valores en porcentaje son relativos al tamaño de fuente del elemento. No se permiten los valores negativos.

La altura de línea también puede darse en la propiedad font junto con un tamaño de fuente.

La propiedad line-height podría usarse para texto a doble espacio:

P { line-height: 200% }

## El selector de id
El selector de id utiliza el atributo id de un elemento HTML para seleccionar un elemento específico.

El ID de un elemento debe ser único dentro de una página, por lo que el selector de ID se utiliza para seleccionar un elemento único.

Para seleccionar un elemento con un ID específico, escriba un carácter de hash (#), seguido del ID del elemento.

La siguiente regla de estilo se aplicará al elemento HTML con id = "para1":
#para1 {
  text-align: center;
  color: red;
}

## El selector de elementos
El selector de elementos selecciona elementos en función del nombre del elemento.

Puede seleccionar todos los elementos <p> en una página como esta (en este caso, todos los elementos <p> estarán alineados en el centro, con un color de texto rojo):
p {
  text-align: center;
  color: red;
}

## Formularios CSS
El ejemplo anterior se aplica a todos los elementos input>. Si solo desea aplicar un estilo a un tipo de entrada específico, puede usar los selectores de atributos:

input[type=text] - Solo seleccionará campos de texto.
input[type=password] - Solo seleccionará campos de contraseña
input[type=number] - Solo seleccionará campos de números

## Para crear un boton

.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}

## Para Márgenes CSS3
Las marginpropiedades CSS se utilizan para crear espacio alrededor de los elementos, fuera de cualquier borde definido.

Con CSS, tienes control total sobre los márgenes. Existen propiedades para establecer el margen para cada lado de un elemento (superior, derecha, inferior e izquierda).

p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}

## Texto CSS3

La colorpropiedad se utiliza para establecer el color del texto. El color es especificado por:

un nombre de color - como "rojo"
un valor HEX - como "# ff0000"
un valor RGB, como "rgb (255,0,0)"
body {
  color: blue;
}

h1 {
  color: green;
}

Alineación del texto
La text-alignpropiedad se utiliza para establecer la alineación horizontal de un texto.

Un texto puede ser alineado a la izquierda o a la derecha, centrado o justificado.
h1 {
  text-align: center;
}

h2 {
  text-align: left;
}

h3 {
  text-align: right;
}

## Diseño CSS - La propiedad de posición

La positionpropiedad especifica el tipo de método de posicionamiento utilizado para un elemento (estático, relativo, fijo, absoluto o adhesivo).
Hay cinco valores de posición diferentes:

-static
-relative
-fixed
-absolute
-sticky

posición: estática;
Los elementos HTML se colocan estáticos por defecto.

Los elementos posicionados estáticamente no se ven afectados por las propiedades superior, inferior, izquierda y derecha.
div.static {
  position: static;
  border: 3px solid #73AD21;
}

posición: relativa;
Un elemento con position: relative;se coloca en relación con su posición normal.

La configuración de las propiedades superior, derecha, inferior e izquierda de un elemento relativamente posicionado hará que se ajuste fuera de su posición normal. El otro contenido no se ajustará para encajar en cualquier espacio dejado por el elemento.
div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}

posición: absoluta;
Un elemento con position: absolute;se posiciona en relación con el antepasado posicionado más cercano (en lugar de posicionarse en relación con la ventana gráfica, como fijo).

Sin embargo; Si un elemento posicionado absoluto no tiene ancestros posicionados, utiliza el cuerpo del documento y se mueve junto con el desplazamiento de la página.
div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 3px solid #73AD21;
}

## CSS Layout - float and clear
La floatpropiedad CSS especifica cómo debe flotar un elemento.

La clearpropiedad CSS especifica qué elementos pueden flotar junto al elemento borrado y en qué lado.
La floatpropiedad se utiliza para posicionar y dar formato al contenido, por ejemplo, permite que una imagen flote hacia la izquierda del texto en un contenedor.

La floatpropiedad puede tener uno de los siguientes valores:

-izquierda - El elemento flota a la izquierda de su contenedor
-derecha- El elemento flota a la derecha de su contenedor
-ninguno: el elemento no flota (se mostrará justo donde aparece en el texto). 
-heredar - El elemento hereda el valor flotante de su padre

img {
  float: right;
}

## The display: inline-block Value
Comparado con display: inline, la principal diferencia es que display: inline-blockpermite establecer un ancho y alto en el elemento.

Además, con display: inline-blocklos márgenes / rellenos superiores e inferiores se respetan, pero con display: inlineellos no se respetan .

Comparado con display: block, la principal diferencia es que display: inline-blockno agrega un salto de línea después del elemento, por lo que el elemento puede ubicarse junto a otros elementos.

span.a {
  display: inline; /* the default for span */
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue; 
  background-color: yellow; 
}

span.b {
  display: inline-block;
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue; 
  background-color: yellow; 
}

## Unidades CSS
CSS tiene varias unidades diferentes para expresar una longitud.

Muchas de las propiedades CSS toman valores "longitud", tales como width, margin, padding, font-size, etc.

La longitud es un número seguido de una unidad de longitud, como 10px, 2em, etc.

Un espacio en blanco no puede aparecer entre el número y la unidad. Sin embargo, si el valor es 0, la unidad se puede omitir.

Longitudes Absolutas
Las unidades de longitud absoluta son fijas y una longitud expresada en cualquiera de ellas aparecerá exactamente como ese tamaño.

h1 {font-size: 1.5cm;}
h2 {font-size: 1cm;}
p {
  font-size: 0.5cm;
  line-height: 1cm;
}

Longitudes Relativas
Las unidades de longitud relativa especifican una longitud relativa a otra propiedad de longitud. Las unidades de longitud relativa se escalan mejor entre diferentes medios de representación.

p {
  font-size: 16px;
  line-height: 2em;
}

div {
  font-size: 30px;
  border: 1px solid black;
}

span {
  font-size: 0.5em;
}

## CSS columnas múltiples
Propiedades de CSS de varias columnas
En este capítulo, aprenderá acerca de las siguientes propiedades de varias columnas:

column-count
column-gap
column-rule-style
column-rule-width
column-rule-color
column-rule
column-span
column-width
## Para cargar el proyecto al GitHub
j.	Para la creación del usuario se debe registrar en la página oficial de GitHub.

k.	Llenamos los datos y nos registramos luego nos dirigimos a el correo que ingresamos y nos       sale un mensaje de confirmación.

l.	Luego ingresamos y creamos un nuevo proyecto

m.	En el cual se almacenará nuestro proyecto creado en HTML5.

n.	Ingresamos el nombre con el cual vamos a guardar nuestro repositorio de la práctica.

o.	Le ponemos en publico para compartirlo con los demás.

p.	Y le damos a crear repositorio 

Una ves credo el repositorio se nos generara una dirección html así:
La cual usaremos para cargar nuestra práctica.

https://github.com/RicardoChuqui/Practica01.git 


q.	Primero descargamos la herramienta Git Bash del siguiente enlace.

r.	La instalación es sencilla solo le damos next y finalizamos una vez realizado esto ya           podemos continuar con la carga del proyecto. 

 https://git-scm.com/download/win
 
 s.	Antes de cargar el proyecto debemos confirmar si el desarrollo de las páginas Web están        correctas para esto usamos la herramienta W3C validator lo encuentras en este enlace.
 
https://validator.w3.org/?fbclid=IwAR2NlzqAR_kIKCA-Bx9byoYRgfGnwXfV6Yr89_RdfyVM_AIAzTnnggV2aIo

t.	Para cargar la práctica abrimos la consola de Windows en el buscador ponemos cmd y le damos     Enter ahora ingresamos los siguientes comandos para registrarnos como usuarios.

u.	Primero nos situamos en la carpeta la cual contiene la práctica.

Cd \ruta completa de la carpeta  

Luego creamos el usuario el mismo que ya creamos en el GitHub

git config --global user.name "usuario del GitHub creado en internet"
 
Luego el correo que ingresamos al crear la cuenta de GitHub.

git config --global  user.email correo@gmail.com

A continuación  el siguiente comando 

git init

Y luego el siguiente


git add .                     

Confirmamos con un commit

git commit -m "Creacion de Proyecto"     

Esta parte es importante aquí ingresamos el link que nos genero al crear el repositorio en GitHub.

git remote add origin https://github.com/RicardoChuqui/Practica01.git

Para cargar usamos el comando push como se muestra a continuación. 

git push -u origin master    


v.	Una ves realizado todos los pasos actualizamos la pagina del repositorio GitHub y nos           aparece cargado el proyecto. 


![alt text](https://github.com/RicardoChuqui/Practica01/blob/master/imagen/logo4.jpg)

## Construido con 🛠️

_Herramientas usadas

* [Editor Brackets](http://brackets.io/) - El editor web usado
* [W3C Validator](https://validator.w3.org/) -Para validar nuestro trabajo
* [Git Bash](https://git-scm.com/downloads) - Para cargar proyectos git
* [GitHub](https://github.com/) - Donde se carga el trabajo realizado


## Tutorial guia 📖

Puedes aprender mucho mas revisando el siguiente Tutorial 01 - 1Curbside-Thai (https://github.com/RicardoChuqui/Practicas)

## Autor ✒️



* **Ricardo Chuqui** - *Trabajo realizado* - [ricardochuqui](https://github.com/RicardoChuqui)

## Licencia 📄

Copyright &copy; 2019-2020 Ricardo Chuqui, todos los derechos reservados.




