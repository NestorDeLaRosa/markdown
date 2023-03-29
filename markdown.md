#
# Markdown #

>## Parrafos y saltos de linea ##
#
Esto nos sirve para poder hacer los saltos de texto en los pparafos, para ello debemos poner dos espacios en blanco despues del texto.
Por ejemplo:   
Esto que estoy separando por el doble espacio en blanco
#
>## Encabezados ## 
#
Los encabezados son algo sencillo de hacer con el markdown, de hecho para poder hacerlo tenemos que poner el signo "#" seguido del texto.  
Un dato interesante es que dependiendo del de la cantidad de "#" que usemos el texto cambiara de tamaño.
#
>## Mejores Prácticas de encabezado ##
#
Para que un encabezado este puesto correctamente debe ir "#" seguido del texto que desees poner como encabezado, no se debe poner "#" con un texto despues ya que no se hara encabezado.  
Tambien nos aconsejan poner lineas en blanco antes y despues del texto, esto para que se vea mas presentable.
# 
>## Saltos de linea ##
#
Para hacer los saltos de linea utilice el <"br">, sin las comillas, de este modo lo que hara es generar un salto de linea. <br>
#
>## Enfasis ##
#
Para ponerlos es colocar las el texto en negritas o bien cursiva.  
#
>## Atrevido ##
#
Para poner el texto en negritas, se debe agregar dos "*" al inicio y al final de una palabra.  
**Esto es un ejemplo de letras en negritas**  
#
>## Prácticas reomendadas ##  
#
Se recomienda que para el uso de las negritas, no usemos los guiones bajos, sino que usemos el "*" cuando queramos poner algo en negritas
#
>## Italico ##
#
Para poner texto en cursiva lo que debemos hacer es algo muy similar al texto en negritas, solo que debemos poner un "*" al inicio y al final.  
*Texto de ejemplo*
#
>## Prácticas recomendadas en cursiva ##
#
Igual que en el tema de cursiva, no se deben usar los guiones bajos, se debe seguir usando el "*" para crear palabras en cursiva.
#
>## Negrita y cursiva ##
#
Para poder colocar el texto con ambos estilos, se debe poner "*" al inicio y despues de lo que queremos poner el negritas y cursiva.  
***Texto de ejemplo***
#
>## Mejores Prácticas en negrita y cursiva ##
#
Como en el tema de la negrita, no se debe usar los guiones bajos, siempre debemos usar los "*" para colocar el texto con el estilo de negrita y cursiva
#
>## Cotizaciones en bloque ##
#
Para crear una cita en bloque, debemos egregar el simbolo de ">" delante de un texto
  
>Esto es una prueba de texto en bloque
#
>## Blockquotes con múltiples prrafos ##
#
Para poder crearlos debemos usar el ">" en cada linea que queramos colocarlo.  
>Esto es   
>una prueba  
>de texto.
#
>## Citas en bloques anidadas ##
#
Para poder generar estas citas debemos poner ">>"delante de un texto
>Esto es un texto de prueba
>>Y este es un texto dentro del texto de prueba
#
>## Blockquotes con otros elementos ##
#
Aqui lo unico que hacemos es aplicar lo que hemos visto hasta el momento

>### Tus calificaciones van bien ###   
>
> - Todo parece en orden  
> - Hasta el momento no hay problemas
> 
> *Todo* va de acorde al plan
#
>## Liza ##
#
Se puede usar para organizar todo en listas  
1.Lapiz  
2.Pluma  
3.Sacapuntas  
4.Computadora  
5.Mouse  
#
>## Listas desordenadas ##
#
Para poder crear este tipo de listas se puede usar "-", "*" o incluso el "+", igual el resultado sera el mismo  
#
>## Comenzar elementos de lista desordenados con números ##
#
Si necesitamos empezar una lista con un numero seguido de un punto, podemos usar la barra invertida seguida de un punto.  
-2020\. Dio incio al año de la pandemia
#
>## Bloques de código
#
Los bloques de código normalmente tienen una sangría de cuatro espacios o una tabulación. Cuando estén en una lista, póngales una sangría de ocho espacios o dos tabulaciones.
#
>## Código ##
#
Para poder marcar una palabra o frase como codigo debemos encerrarlo en (`).
#
>## Escapar de los acentos graves ##
#
Si la palabra o frase que desea denotar como código incluye uno o más acentos graves, puede escapar encerrando la palabra o frase entre dobles acentos graves ( ``).
#
>## Reglas horizontales ##
#
Para crear una regla horizontal, use tres o más asteriscos ( ***), guiones ( ---) o guiones bajos ( ___) en una sola línea.
#
>## Enlaces ##
#
Para crear un enlace, encierre el texto del enlace entre corchetes (p. ej., [Duck Duck Go]) y luego sígalo inmediatamente con la URL entre paréntesis    Ejemplo (https://duckduckgo.com).
#
>## Agregar títulos ##
#
Opcionalmente, puede agregar un título para un enlace. Esto aparecerá como información sobre herramientas cuando el usuario se desplace sobre el enlace.
#
>## URL y direcciones de correo electronico ##
#
Para convertir rápidamente una URL o una dirección de correo electrónico en un enlace, enciérrelo entre "<>"
#
>## Formateo de enlaces ##
#
Para enfatizar los enlaces, agregue asteriscos antes y después de los corchetes y paréntesis
#
>## Vínculos de estilo de referencia ##
#
Los enlaces de estilo de referencia son un tipo especial de enlace que hace que las URL sean más fáciles de mostrar y leer en Markdown. Los enlaces de estilo de referencia se construyen en dos partes: la parte que mantiene en línea con su texto y la parte que almacena en otro lugar del archivo para que el texto sea fácil de leer.  
#
>## Dar formato primera parte del enlace ##
#
La primera parte de un vínculo de estilo de referencia se formatea con dos conjuntos de corchetes. El primer conjunto de corchetes rodea el texto que debería aparecer vinculado. El segundo conjunto de corchetes muestra una etiqueta que se usa para apuntar al enlace que está almacenando en otra parte de su documento.  
#
>## Formateo de la segunda parte del enlace ##
#
La segunda parte de un vínculo de estilo de referencia se formatea con los siguientes atributos:

1. La etiqueta, entre paréntesis, seguida inmediatamente por dos puntos y al menos un espacio (p. ej., [label]: ).
2. La URL del enlace, que opcionalmente puede encerrar entre paréntesis angulares.
3. El título opcional del vínculo, que puede encerrar entre comillas dobles, comillas simples o paréntesis.  
#
>## Un ejemplo de juntar las partes ##
#
Digamos que agrega una URL como un enlace de URL estándar a un párrafo y se ve así en Markdown:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.  
Aunque puede apuntar a información adicional interesante, la URL que se muestra en realidad no agrega mucho al texto sin formato existente, aparte de dificultar la lectura. Para arreglar eso, podría formatear la URL de esta manera:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"  
#
>## Imagenes ## 
 #
 Para agregar una imagen, agregue un signo de exclamación ( !), seguido del texto alternativo entre paréntesis y la ruta o URL del recurso de imagen entre paréntesis. Opcionalmente, puede agregar un título entre comillas después de la ruta o URL  
 ![The San Juan Mountains are beautiful!](https://images2.alphacoders.com/941/thumb-1920-941898.jpg)  
 Como podemos ver aqui llamamos una imagen pero usando una URL
 #
 >## Vinculación de Imágenes ##
#
Para agregar un enlace a una imagen, encierre el Markdown de la imagen entre paréntesis y luego agregue el enlace entre paréntesis. 

 ![Intentando buscar la imagen](https://usagif.com/wp-content/uploads/loading-11.gif "Cargando") 
 En este caso si pasas el maouse sobre la imagen te mostrara un texto.
 #
 >## Personajes que escapan ##
#
Para poder mostrar un carácter que de otro modo se usuaría para dar formato al texto, se debe poner una barra invertida delante del caracter.  
Ejemplo:   
\ * sin la barra invertida esto seria una lista desordendad  
Ejemplo sin la barra invertida:  
* Esto es una lista ordenada sin la barra invertida
#  
>## HTML ##
#
Muchas aplicaciones de Markdown le permiten usar etiquetas HTML en texto con formato de Markdown. Esto es útil si prefiere ciertas etiquetas HTML a la sintaxis Markdown. Por ejemplo, a algunas personas les resulta más fácil usar etiquetas HTML para imágenes