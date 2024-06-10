# Clase 3: Lectura

## Aprende HTML

1. ¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?

    - Para cuando se quiere listar elementos que no tengan una secuencia especifica
2. ¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?

    - ul {
    list-style-type: ***;
    }
3. ¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?

    - `<ol>`: Cuando el orden el que los elementos se presentan es importante
    - `<ul>`: Cunado el orden de los elementos no requiera ser especifico
4. Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada

    - `<ol start="7">`
    - `<ol type="i">`

## Aprende CSS

1. Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?

    - `Margin` es como el caballero protegiendo un castillo. Situado en el exterior, manteniendo distancia entre el castillo y el mundo exterior, asegurándose que se mantengan alegados. Su rol es mantener a raya otros elementos, garantizando espacio alrededor del contenido.

    - `Padding` es el acolchado interior del castillo, protegiendo el contenido del borde de las paredes. Su rol es dar un espacio interno, asegurando que el contenido no toque los bordes.

    - Juntos, Margin y Padding trabajan para asegurar que el box tenga el espacio tanto por fuera como por dentro, protegiendo y destacando el contenido.
2. Enumera y describe las cuatro partes de un box del elementos HTML según el box model.

    1. Content: Donde se presenta el contenido
    2. Padding: El espacio entre el contenido y el borde del elemento.
    3. Border: El borde alrededor del padding y el contenido.
    4. Margin: El espacio afuera del borde, separando el elemento de otros elementos circundantes.

## Aprende JS

1. ¿Qué tipos de datos puedes almacenar en un Array?
    - Puedes almacenar: cadenas, números, objetos, u otras variables, incluso otros arreglos.
2. ¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?

    ```text
     const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```

    - Es valido ya que se puede crear arrays compuestos por otros arrays para crear listas de objetos mas complejas, Y se puede acceder a sus valores usando notación de corchetes, i.e:
    `let smithAge = people[1][1];`  
    Que crearía una variable `SmithAge` desde el array `people` en su mismo array `[1]=['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing']` y seleccionando el valor `[1]` dentro del mismo, osea `[40]`

3. Enumera cinco operadores abreviados de asignación en javascript y describe lo que hacen.

    1. +=: ej. `a += b` es equivalente a `a = a + b.`
    2. -=: ej. `a -= b` es equivalente a `a = a - b.`
    3. *=: ej. `a *= b` es equivalente a `a = a * b.`
    4. /=: ej. `a /= b` es equivalente a `a = a / b.`
    5. %=: ej. `a %= b` es equivalente a `a = a % b.`

4. Lee el código a continuación, evalúa la última expresión y explica cuál sería el resultado y por qué.  

    `let a = 10;`  
    `let b = "dog";`  
    `let c = False;`  
    `//evalúa esto`  
    `(a+c)+b;`  

    - El resultado seria: `10dog`, ya que JS convierte `False` en un 0 cuando se usa en una operación aritmética lo que dejaria la operaioon siendo `(10+0)+dog`

5. Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.

    - Un ejemplo para usar una declaración condicional podría ser verificar si un usuario ha iniciado sesión antes de permitirle acceder a una página de perfil:

     ```text
        if (usuario.isSesiónIniciada) {
        MostrarPaginaDePerfil();
        } else {
        RedirigirPaginaDePerfil();
        }
     ```

## Cosas de las que quiero saber mas

- Mas usos útiles para los arrays

### Fuentes

- [HTML: Lenguaje de etiquetas de hipertexto](https://developer.mozilla.org/es/docs/Web/HTML)
- [`<ol>`: The Ordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [ul](https://developer.mozilla.org/es/docs/Web/HTML/Element/ul)
- [CSS](https://developer.mozilla.org/es/docs/Learn/CSS)
- [El modelo de caja](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model)
- [JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript)
- [Arrays](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/Arrays)
- [Expressions_and_Operators](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Conditionals](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)
