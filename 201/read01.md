# Clase 01: Lectura

Aprender y repasar como funcionan las paginas web y como tu código interactúa con el navegador es importante para todo programador y/o estudiante de programación para aprender, reforzar y mantener el conocimiento que tienes fresco, y cuando aprendas algo nuevo y tengas errores los conocimientos básicos te ayudaran a perfeccionar tu habilidad de escribir código.

## Fundamentos de JavaScript

**Preguntas:**

1. Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.

   En la red viaja HTTP,  
   paquetes de datos va a repartir.  
   Del servidor al cliente un ir y venir,  
   respuestas y solicitudes hasta el fin.

2. Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.

   - HTML: Se crea el DOM, una estructura jerárquica de nodos.  
   - CSS: Se construye el CSSOM, aplicando estilos a los nodos del DOM.
   - JavaScript: Se interpreta y ejecuta, manipulando el DOM y CSSOM.

3. ¿Cómo puedes encontrar imágenes para agregar a una página web?

    - Bancos de imágenes gratuitas
    - Usar tus propias imágenes o creadas por ti

4. ¿Cómo creas una String en comparación con un Number en Javascript?

   Para crear una String solo colocas tu variable de texto entre comillas("")
   i.e.

   -Sting
   'Let String = "MiString"'

   -Number
   'let Numero = 17'

5. ¿Qué es una Variable y por qué son importantes en JavaScript?

   Las variables son contenedores de información, cuando declaras una variable la declaras como Let, Cons y/o Var, y cada uno tiene un uso distinto. Y las variables son importantes en JS por los siguientes motivos:

   - Almacenamiento: Una vez declarada una variable se almacena y su información se puede manipular a lo largo del programa
   - Reutilización: Facilitan la utilización de datos varias veces sin ser repetitivo
   - Mantenibilidad: Hacen que la legibilidad del código sea simple y fácil de mantener y manipular ya que se pueden mantener en un solo lugar o donde las necesites

## Primeros pasos con HTML

**Preguntas:**

1. ¿Qué es un atributo en HTML?

    Un atributo de HTML le proporciona información a un elemento y este se define mediante su etiqueta

2. Describe la anatomía de un elemento en HTML.

    la anatomía de un elemento HTML es la siguiente:
    - Etiqueta de apertura
    - Atributos
    - Contenidos
    - Etiqueta de cierre

3. ¿Cuál es la diferencia entre las etiquetas `<article>` y `<section>`?

    - `<article>` Para contenido independiente y autónomo, asi como un artículo de blog, foro o comentario.
    - `<section>` Agrupa contenido relacionado dentro de un documento HTML, no necesariamente independiente o autónomo.

4. Qué elementos se incluyen en una página web “típica”?

    Pueden ser:
    - `<header>`
    - `<nav>`
    - `<main>`: Contiene `<article>`, `<section>`, y `<div>`.
    - `<aside>`
    - `<footer>`

5. ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?

    - Los metadatos en HTML, asi como descripciones, palabras clave, autor y título de la página, proporcionar información, y dan a entender al buscador el contenido y la temática de la página, lo que ayuda a clasificarla en los resultados de búsqueda.

6. ¿Cómo se utiliza la etiqueta `<meta>` en HTML cuando se quiere especificar metadatos?

    - Puedes especificar: conjunto de caracteres, descripción de la página, palabras clave y título de la página. Y se coloca dentro del elemento `<head>` en el HTML

## Misceláneos

[**¿Cómo empiezo a diseñar mi sitio web?.**](https://developer.mozilla.org/es/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

1. ¿Cuál es el primer paso para diseñar una página web?

    - Para diseñar una página web debes pensar en la audiencia y los objetivos del sitio.

2. ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?

    - La pregunta más importante es "¿Qué quiere lograr el sitio y para quién lo está diseñando?".

[**Semántica.**](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

1. ¿Por qué se debe utilizar un elemento `<h1>` en vez de un `<span>` para mostrar un título de primer nivel?

    - Se hace porque proporciona estructura y semántica a al código y ayuda a entender la importancia de las partes del texto

2. ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?

    - Ayudan a tener una pagina legible y código legible para: el lector, los buscadores y el programador

[**¿Qué es JavaScript?**](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

1. Describe 2 cosas que requieran de JavaScript en el navegador.

    - Validación de datos: i.e. tener una cuenta que solo una persona que tenga el nombre y contraseña pueda acceder
    - Interacción del usuario: i.e. como la pagina interactúa con los imputs del usuario

2. ¿Cómo se puede añadir JavaScript a un documento en HTML?

    Hay 3 formas de hacerlo
    - Usando `<Script>` hay 2 formas de usar JS en tu código
        1. escribir el código en el mismo HTML
        2. hacer un link a un archivo JS externo
    - Usando Controladores de JS en linea en el mismo HTML que luego interactúan con tu código en `<script>`  
        i.e `<button onclick="()">Botón!</button>`

## Cosas que quiero saber

Por ahora nada.

### Fuentes

- [Como Funciona la web?](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [La apariencia de tu sitio web](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- [Fundamentos de JS](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Primeros pasos con HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- [Documentación y estructura web](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [Metadatos en HTML.](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
