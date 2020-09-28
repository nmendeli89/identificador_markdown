<!-- Esto es un comentario -->

<!-- HEADINGS -->

# Mi titulo en h1 
## Mi titulo en h2
### Mi titulo en h3{#inicio}
#### Mi titulo en h4
##### Mi titulo en h5
###### Mi titulo en h2

<!-- Con un salto de linea lo escribe todo en la misma linea -->

Esto es un texto en *italica*
Esto es un texto en **negrita** 
Este es un texto ~~tachado~~

<!-- En cambio con dos saltos de lineas lo escribe todo en lineas diferentes -->

Esto es un texto en *italica*

Esto es un texto en **negrita** 

Este es un texto ~~tachado~~

<!-- Lista desordenada -->

<!-- Hay de dos maneras de hacerlo, con un asterisco * o con un más + -->
Lista desordenada:{#listdes}
* Manzana
* Naranja
* Plátano
* Pera
* Uva

+ Manzana
+ Naranja
+ Plátano
+ Pera
+ Uva

<!-- Lista ordenada -->
Lista ordenada:{#listor}
1. Manzana
2. Naranja
3. Plátano
4. Pera
5. Uva

<!-- Lista desordenada con subitems -->
* Manzana
    * Manzana ácida
        * Verde
            * Lindo
                * Lloro pues a partir de aqui el item es el mismo solo cambio el margen
    * Manzana roja
    * Manzana verde
    * Manzana amarilla
* Naranja
    * Mandarina
* Plátano
* Pera
* Uva

<!-- Lista ordenada -->
1. Manzana
    1. Manzana ácida
        1. Verde
        2. Roja
    2. Manzana verde
    3. Manzana roja
2. Naranja
3. Plátano
4. Pera
5. Uva

<!-- Enlaces -->

<!-- Si pasas el ratón por encima de Documentación de Markdown aparece la dirección web pues no añadimos etiqueta  -->
[Documentación de Markdown](https://es.wikipedia.org/wiki/Markdown)


<!-- En este caso, si pasas el ratón por encima de Documentación de Markdown aparece el texto "Markdown es un lenguaje de marcado ligero." pues es lo que añadimos en la etiqueta  -->

[Documentación de Markdown](https://es.wikipedia.org/wiki/Markdown "Markdown es un lenguaje de marcado ligero.")

<!-- Citas -->

> Esto es una cita

<!-- Lineas -->
<!-- Hay dos maneras: La primera es con tres guiones seguidos -->

--- 
 
 <!-- Y la otra es con tres subguiones seguidos -->
___

<!-- Codigo -->
<!-- De una sola linea -->

`console.log('Hola mundo')`

<!-- O tambien -->

`
console.log('Hola mundo')
`

<!-- De varias lineas -->

```

<!DOCTYPE HTML>

<html>

  <head>

    <meta charset="utf-8" />

    <title>Ejemplo1</title>

  </head>

  <body>

    <p>Párrafo de ejemplo</p>



    <p>Texto HTML</p>



    <p>Primera página</p>

  </body>

</html>
```

<!-- Tambien se puede especificar el lenguaje y asi resaltar en colores -->
<!-- De una sola linea -->

<!-- En este caso ya no te sirve el hacerlo con unas comillas ni escribirlo en una linea, requiere minimo de tres lineas, una para las comillas de apertura con el lenguaje, otra para las comillas de cierre y otra como mínimo para el codigo -->

```javascript 
console.log('Hola mundo')
```

```python 
print("Hola mundo")
```

```html
<h1>Hola mundo</h1>
```



<!-- De varias lineas -->

```html

<!DOCTYPE HTML>

<html>

  <head>

    <meta charset="utf-8" />

    <title>Ejemplo1</title>

  </head>

  <body>

    <p>Párrafo de ejemplo</p>



    <p>Texto HTML</p>



    <p>Primera página</p>

  </body>

</html>
```

<!-- Tablas -->

| Titulo 1 | Titulo 2 | Titulo 3 |
| -------- | -------- | -------- |
| Texto 11 | Texto 12 | Texto 13 |
| Texto 21 | Texto 22 | Texto 23 |
| Texto 31 | Texto 32 | Texto 33 |

<!-- En las barras - (es obligatoria que este en la segunda linea de la tabla) se puede poner todo barras o dos puntos al comienzo y/o al final -->

| Titulo 1 | Titulo 2 | Titulo 3 |
| :------: | -------: | -------- |
| Texto 11 | Texto 12 | Texto 13 |
| Texto 21 | Texto 22 | Texto 23 |
| Texto 31 | Texto 32 | Texto 33 |


*[ESO]: Enseñanza secundaria obligatoria 
*[PAU]: Pruebas de acceso a la universidad

La ESO va desde primero hasta cuarto. Todo aquel que apruebe la ESO puede acceder a bachilleto para hacer las PAU.


Esto es un texto con nota al pie [^nota1] y esta es otra nota [^nota2]

[^nota1]: Esto es una nota al pie de página.
[^nota2]: Esto es la segunda nota al pie.

<!-- Imagenes -->

<!-- Por web, si falla la imagen, si no la encuentra, sale lo que este en [] -->
![Logo de everis](https://www.fororecursoshumanos.com/wp-content/uploads/2017/03/Everis.jpg)

<!-- Por imagen local en el proyecto, si falla la imagen, si no la encuentra, sale lo que este en [] -->
![Portatil de everis](portatil.jpg)

<!-- Ahora si pasas el ratón por encima de la foto te sale una eqtiqueta con el texto que insertes -->
![Logo de everis](https://www.fororecursoshumanos.com/wp-content/uploads/2017/03/Everis.jpg "Este es el clásico logo de Everis")


![Portatil de everis](portatil.jpg "Este es el portátil de Everis que se da por defecto a sus empleados")

<!-- Markdown con Github -->

<!-- Tutum (Lista con items marcados o no), en este visualizador no se ve -->

<!-- Si se pone [x] significa el elemento esta marcado o realizado es decir que tiene un check, en cambio [ ] significa que no se marcado o no realizado es decir no tiene un check -->

* [x] Tarea 1
* [ ] Tarea 2
* [ ] Tarea 3
* [x] Tarea 4

<!-- Para mencionar a un usuario de Github, es decir cuando suba el repositorio dicho usuario (el que aparezca despues del arroba) recibira una notificación -->

@nmendeli89

<!-- Emoji -->

<!-- Simplemente es buscar el emoji que quieras en la web https://gist.github.com/rxaviers/7360908 o buscando github emoji o github emoji markdown y copiar y pegar el codigo que te facilite, sin requerir nada mas (todos empiezan y terminan por :) -->

:smiley:

:sweat_smile:

:yum:

:+1:

<!-- Para saber más acceda a https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet o simplemente busque github markdown -->
Para saber más clique [aquí](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


[Ir al inicio](#inicio)

[Ir a la lista desordenada](#listdes)

[Ir a la lista ordenada](#listor)


Primer termino
 : Primera definición
 : Segunda definición

Segundo termino
 : Segunda definición
