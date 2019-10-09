# Tarea 1.1 Marc McLarty
## Markdown y Github
### Tienes que explicar los principales formatos que se pueden aplicar a un documento escrito en este lenguaje, aplicándolo a diferentes ejemplos:

* Header: se utiliza para poner títulos, utilizando `#`, cuantas más `#` pongamos, menor tamaño tendrá el título hasta un máximo de 6. Es la alternativa de h1, h2,... de HTML.
    * Habrá que escribir:
    ```
    # Título 1
    ## Título 2
    ``` 
    Y nos mostrará:
    # Título 1, 
    ## Título 2
  
* Emphasis: es utilizado para poner:                                                
    * Itálica o cursiva: *Marc* o _Marc_ -> ```*Marc* o _Marc_```
    * Negrita: **Marc** o __Marc__ -> ```**Marc** o __Marc__```
    * Tachado: ~~Marc~~ -> ```~~Marc~~```
    * Puedes combinarlas también: **Marc _McLarty_ ~~Perpiña~~** -> ```**Marc _McLarty_ ~~Perpiña~~**```

* List: estas las utilizaremos para crear listas. Para ello utilizaremos los códigos ```1.```, ```2.```, etc. Esto lo que hará sera crear lsita con números.
    * Ejemplo escrito: 
    ```
    1. Marc
    2. McLarty
    ```
    Lo que nos mostrará
    1. Marc  
    2. McLarty

* List: también podremos utilizar puntos para crear listas ```*, -``` o ```+```.
    * Ejemplo escrito: 
    ```
    * Marc
    - McLarty
    + Perpiña
    ```
    Lo que verás:
    * Marc 
    - McLarty
    + Perpiña

* Links: nos permitirá hacer un escrito el cual nos llevará a una página web, utilizando primero las corchetes ```[]``` para poner lo que quieres escribir y luego los paréntesis ```()``` para indicar donde a donde nos va a llevar al hacer click.
    * Ejemplo escrito:
    ```
    [Si haces click te llevará a la página Web "Marca"](https://www.marca.com)
    ```
    Lo que vas a ver:
    [Si haces click te llevará a la página Web "Marca"](https://www.marca.com)

* Images: es utilizado para poner imágenes, se utilizará el código ```![alt text](Habrá que indicar donde se encuentra la imagen)```
    * Lo que habrá que escribir:
    ```
    Markdown:
    ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)
    ```
    * Lo que se verá:
    Imagen de Markdown:
    ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

* Code and Syntax Highlighting: se utiliza para indicar que parte es código y que no se ejecute. Para ello se utilizará entre el código los acentos a la izquierda (`).
    * El `#` es código y por lo tanto no lo ejecutará.

* Tables: para crear tablas habre que utilizar el siguiente código:
    ```
    * Lo que hay que escribir:
    | Tables        | Are           | Cool  |

    | ------------- |:-------------:| -----:|

    | col 3 is      | right-aligned | $1600 |

    | col 2 is      | centered      |   $12 |

    | zebra stripes | are neat      |    $1 |
    ```
    * Lo que verás:

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

* Blockquodes: se utiliza para bloquear una línea de parrafo y todo se escriba seguido, además, quedará como subrayado. Para realizar esta función utilizaremos al principio `>`:
    * Lo que habrá que escribir:
    ```
    > Marc 
    > McLarty
    > Perpiña
    ```
    * Lo que se verá:
    > Marc
    > McLarty 
    > Perpiña

* Blockquodes: Y para quitar la función y empezar con otra, habrá que dejar un espacio entre ellos.
    ```
    * Lo que hay que escribir:
    > Marc
    > Mclarty

    >Perpiña
    ```
    * Lo que verás:
    > Marc 
    > McLarty

    > Perpiña

* Inline HTML: podrás utilizar comandos de HTML. Lo que a veces no podrás intercambiar comandos de HTML con los de Markdown.
    * Lo que hay que escribir:
    ```
    <h4>Será un título pequeño.</h4>
    <i>Lo verás en itálica con comandos HTML.</i>
    
    <h4>Markdown en HTML</h4>
    <p>Estos *comandos* __no__ ~~funcionarán~~. Así que habrá que utilizar HTML. </p>
    ```
    * Lo que verás:
    <h4>Será un título pequeño.</h4>
    <i>Lo verás en itálica con comandos HTML.</i>
    
    <h4>Markdown en HTML</h4>
    <p>Estos *comandos* __no__ ~~funcionarán~~. Así que habrá que utilizar HTML. </p>

### ¿Qué codificación de caracteres tiene este archivo de texto? Contesta el mismo documento Markdown.
El tipo de codificación que se ha utilizado es el UTF-8.

### Tienes que explicar la función de las principales instrucciones de git (clone, add, commit, push, pull) y poner algún ejemplo.
* `git clone <url>`: Lo que hace es una cópia del un repositorio remoto.
    * Ejemplo: git clone `<https://github.com/MMcLarty/McLartyPerpi-aMarc_Tasca11>`
* `git add (-u) (nombrefichero).(extensión)`: Esta función añade el el contenido al index
    * Ejemplo: git add -u tarea1.1.md
* `git commit (-m "mensaje que quieres poner")`: esto lo que hace es guardar los archivos permanentemente en historial de versiones.
    * Ejemplo: git commit -m "Mi primer repositorio"
* `git push origin master`: manda todos los archivos válidos al repositorio.
* `git pull origin master`: descarga todos los archivos que tengas en el fichero.














