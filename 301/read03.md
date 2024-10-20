# Lecturas: Pasar funciones como props

## Documentación de React - listas and keys

1. ¿Qué retorna .map()?
    - `.map()` retorna un nuevo array con los resultados de aplicar una función a cada elemento del array original.

2. Si quiero recorrer un bucle a través de un array y mostrar cada valor en JSX, ¿cómo lo haría en React?
    - Usaría el método .map() para iterar a través del array y devolver un elemento JSX para cada valor.

3. Cada elemento de la lista necesita un ____ único.
    - Key

4. ¿Cuál es el propósito de una key?
    - La key es utilizada por React para identificar qué elementos han cambiado, agregado o eliminado. Ayuda a optimizar el proceso de actualización del DOM.

## El Operador Spread

1. ¿Qué es el operador spread?
    - El operador spread (...) es una sintaxis en JavaScript que permite expandir elementos de un iterable (como un array o un objeto) en lugares donde se esperan múltiples elementos.

2. Enumera 4 cosas que el operador spread puede hacer.
    - Clonar un array o un objeto.
    - Combinar arrays.
    - Añadir nuevos elementos a un array.
    - Combinar objetos.

3. Da un ejemplo del uso del operador spread para combinar dos arrays.

     ```js
    const array1 = [1, 2, 3];
    const array2 = [4, 5, 6];
    const combinado = [...array1, ...array2];
    console.log(combinado);
    ```

4. Da un ejemplo del uso del operador spread para añadir un nuevo elemento a un array.

    ```js
    const frutas = ['manzana', 'naranja'];
    const nuevasFrutas = [...frutas, 'plátano'];
    console.log(nuevasFrutas);
    ```

5. Da un ejemplo del uso del operador spread para combinar dos objetos en uno.

    ```js
    const obj1 = { nombre: 'Juan', edad: 30 };
    const obj2 = { trabajo: 'Desarrollador', pais: 'España' };
    const combinado = { ...obj1, ...obj2 };
    console.log(combinado);
    ```
