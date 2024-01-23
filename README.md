# ASIX1_M4_APUNTES

<h1>MARKDOWN</h1>
Para poner una palabra en una topologia de cursiva se pone con dos asteriscos dentro de la palabra *ejemplo* o tambien _ejemplo_ poniendo las dos rayas hacia abajo tambien funciona.
Para poner la palabra en negrita son la mimsmas opciones que en la de cursiva pero en este caso cambia poniendo dos asteriscos acada lado **ejemplo** __ejemplo__ y estaran las dos palabras en negrita.

Para hacer un menu de opciones de puede hacer de dos maneras que son poniendo el numero que seria

1. Primera opcion del menu
2. Segunda opcion del menu
3. Tercera opcion del menu

O de esta manera tambien se puede hacer:

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
   1. Primer Submenu
   2. Segundo submenu
- Cuarta opcion de lista desordenada
   * Tercer submenu
   * Cuarto submenu
+ Quinta opcion de lista desordenada
+ Sexta opcion de lista desordenada

<h1>HTML</h1>

La estructura del html que nos vamos a encontrar en nuestra aplicacion que en este caso es la del Visual Studio Code.
Los tres acentos abiertos lo que nos hace, que la estructura que pongamos no se ejecute hace que solo salga por pantalla como si fuera un comentario
```
<html>
   <head>
   </head>
   <body>
      <p> Esto es un texto</p>
    </body>
<html>
```
Para poner un enlace en nuestra pagina web ponemos las siguientes instrucciones
Ponemos los dos corchetes para poner en medio un texto informativo del enlace despues cerramos los corchetes, despues abrimos parentesis y ponemos una URL cualquiera despues ponemos entre comillas de que setrata esa URL que hemos insertado
```
[Esto es un enlace](https://joan23.fje.edu "Enlace a la web del cole")
```
Para crear una tabla ponemos | esta raya y dentro lo que queramos poner dentro de nuestra tabla despues podemos poner |centrada| ara que se centre el texto que esta dentro de la tabla


|Primera Col.|Segunda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

Para poner una imagen en nuestra pagina de html tendremos que utilizar el siguiente atributo de img
<img src="darth1.jpg">

Lo el br que hace es que termite crear un salto de linea, es un elemento vacio que no tiene nada dentro.
<br>
Y el hr nos hace un intro en el que nos inserta una linea de punta a punta de la pagina web
<hr>

En el html podemos hacer una lista de elementos que es un conjunto de elementos en los que se puede agrupar las etiquitas: 
Se puede hacer con la etiqueta ol que es la para listas ordenadas como en este ejemplo de una lista de videojuegos ordenada con la etiqueta ol y cada elemento dentro tiene la etiqueta de li:
<ol>
   <li>The Legend of Zelda: Breath of the Wild</li>
   <li>Super Mario Odyssey</li>
   <li>Animal Crossing: New Horizons</li>
   <li>Splatoon 2</li>
   <li>Super Smash Bros. Ultimate</li>
   <li>Mario Kart 8 Deluxe</li>
   <li>Pokémon Sword and Shield</li>
   <li>Luigi's Mansion 3</li>
   <li>Fire Emblem: Three Houses</li>
   <li>Super Mario Maker 2</li>
</ol>
Y con la etiqueta ul hacemos una lista desordenada utilizaremos el mismo ejemplo de los videjuegos:
<ul>
  <li>The Legend of Zelda: Breath of the Wild</li>
  <li>Super Mario Odyssey</li>
  <li>Animal Crossing: New Horizons</li>
  <li>Splatoon 2</li>
  <li>Super Smash Bros. Ultimate</li>
  <li>Mario Kart 8 Deluxe</li>
  <li>Pokémon Sword and Shield</li>
  <li>Luigi's Mansion 3</li>
  <li>Fire Emblem: Three Houses</li>
  <li>Super Mario Maker 2</li>
</ul>

Para poner links o URL que nos direccionen a otras paginas ponemos la etiqueta a que la estructura de la etiqueta es la siguente:

```<a heref="direccion de URL" alt="para poner un texto alternativo en la url">
```

Para poner comentario en nuestro codigo es poniendo esto:
```<!--Para comentar nuestro codigo para enterder lo ->
```

Para cambiar la tipografia de nuestra pagina web tendremos que poner un link en el head de nuestro archivo.html que es poner este link en el head:
```
<script src="https://kit.fontawesome.com/e406714e56.js" crossorigin="anonymous"></script>
```



<h1>Visual Studio Configuracion</h1>

Cuando abrimos el visual studio code veremos una pagina completamiente en blanco y tendremos que ir a la barra de tareas de arriba del visual poner new text file y seleccionamos el tipo de formato que vamos a  utilizar.
En la primera linea nos salra para poner el tipo de lenguaje que tendra nuestra pagina.
Si elegimos html abajo a la derecha nos saldra el formato del lenguaje de la pagina.
<img src="VisualStudio_formato.png">
Podemos hacer que nos haga una pequeña estructura para html si ponemos html:5, le damos a intro y nos saldra una pequeña estructura.
<img src="Estructura_de_html.png">
<img src="Estructura.png">
<br>
Vemos que en la estructura hay el tipo de lenguaje, luego el idioma en el que esta puesta la pagina que en este caso es HTML en la tercera linea tendremos el comando head con su contenido dentro y luego se cierra en la septima linea, depues en la octava linea tenermos el comando body que es donde podremos todo el contenido para crear nuestra pagina web.





