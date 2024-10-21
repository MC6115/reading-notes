# Lecturas: Juntando todo

## Documentación de React - Pensar en React

1. ¿Qué es el principio de responsabilidad única y cómo se aplica a los componentes?
    - Un componente debe encargarse de una sola tarea o tener una razón única para cambiar. Esto facilita la reutilización y mantenimiento en React.

2. ¿Qué significa crear una versión ‘estática’ de tu aplicación?
    - Es construir la UI sin funcionalidad ni interactividad, solo mostrando datos.

3. Una vez que tienes una aplicación estática, ¿qué necesitas añadir?
    - Se añade interactividad, manejando el state y los eventos de usuario.

4. ¿Cuáles son las tres preguntas que puedes hacer para determinar si algo es state?
    1. ¿Es pasado como prop?
    2. ¿Puede cambiar con el tiempo?
    3. ¿Se puede derivar de otros datos?

5. ¿Cómo se puedes identificar dónde se necesita ubicar el state?
    - El state debe colocarse en el componente más cercano que lo necesite o lo comparta con otros.

## Higher-Order Functions

1. ¿Qué es una “función de orden superior”?
    - Función que recibe o devuelve otras funciones.
2. Explora la función greaterThan tal y como se define en la lectura. Con tus propias palabras, ¿qué hace la línea 2 de esta función?
    - Crea una nueva función que verifica si el número m es mayor que n
3. Explica cómo funciona map o reduce con respecto a las funciones de orden superior.
    - map: Aplica una función a cada elemento de un array y devuelve un nuevo array.
    - reduce: Aplica una función para reducir un array a un solo valor acumulado.

### Fuentes

- [Pensar en React](https://es.react.dev/learn/thinking-in-react)
- [Higher-Order Functions](https://eloquentjavascript.net/3rd_edition/05_higher_order.html#h_xxCc98lOBK)
