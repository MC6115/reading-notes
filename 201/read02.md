# Clase 02: Lectura

## Introducción a HTML

1. ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?

   - Es importante para mejorar tanto su accesibilidad como el SEO de tu pagina.

2. ¿Cuántos niveles de encabezado existen en HTML?

    - Hay 6 niveles, del h1 al h6

3. ¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?

    - `<sup>` puede usarse para superinduce asi como exponentes y `<sub>` para subindices como formulas químicas e indices matemáticos

4. Al utilizar el elemento `<abbr>`, qué atributo se debe añadir para proporcionar una ampliación del término?

    - Se puede usar el atributo `title`

## Aprende CSS

1. ¿De qué formas podemos añadir CSS a nuestro HTML?

    - Se puede hacer de 3 formas
        1. En linea: Con el atributo style das los comandos CSS en la misma etiqueta que quieres editar
        2. Interno: Con `<Styles>` creas el bloque de CSS en el mismo documento HTML
        3. Externo: Usas `<link>` para que un documento CSS externo se aplique al HTML

2. ¿Por qué deberíamos evitar utilizar estilos inline?  

    - Porque puede crear errores en tu código o redundancias, los cuales dificultan el mantenimiento, asi que se recomienda hacerlo de forma Interna, en un solo bloque, o tener un documento externo
w
3. Revisa el código a continuación y responde a las siguientes   preguntas:  
    - ¿Qué representa el selector?
        - representa que los estilos se aplicaran a todas as etiquetas `<h2>`
    - ¿Qué componentes son declaraciones CSS?
        - Las declaraciones son: `color: black;` y `padding:5px;`
    - ¿Qué componentes se consideran propiedades
        - Color y Padding

    ```text
    ¿Qué componentes se consideran propiedades?
    h2 {
     color: black;
     padding: 5px;
    }

## Aprende JS

**Fundamentos de JavaScript.**

1. ¿Qué tipo de dato es una secuencia de texto entre comillas simples?
    - Un `String`
2. Enumera 4 tipos de operadores en JavaScript.
    - Aritméticos
    - Lógicos
    - De Comparación
    - De Asignación
3. Describe un problema práctico que puedes resolver con una función.
    - Hacer una calcinación: i.e. Graficar los puntos de un plano cartesiano cuando el usuario te da la pendiente de una recta.

**Tomando decisiones en tu código — condicionales.**

1. Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará.
    - Condición, Verdadera
2. ¿Cuál es el uso del `else if`?
    - Especificar una nueva condición a comprobar si la condición anterior `if-else` resulta falsa, y te permite encadenar condiciones
3. Enumera 3 tipos de operadores de comparación.
    - Igualdad(==)
    - Desigualdad(!=)
    - Mayor que(>)
4. ¿Cuál es la diferencia entre los operadores lógicos `&&` y `||`?
    - `&&` devuelve verdadero si ambas condiciones son verdaderas
    - `||` devuelve verdadero si al menos una es verdadera

## Cosas de las que quiero saber más

- Por ahora no entiendo muy bien como encadenar if-else con else-if. Investigar mas
- No he usado Operadores de asignación. Jugar con ellos a futuro

### Fuentes

- [Introducción a HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML)
- [Fundamentos de texto en HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [Formateo de texto avanzado](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
- [Cómo se estructura el CSS](https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/How_CSS_is_structured)
- [Fundamentos de JavaScript](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Tomando decisiones en tu código — condicionales](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)
