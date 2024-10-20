# Lecturas: React y Formularios

## How to use Forms in React

1. ¿Qué es un ‘Componente Controlado’?
    - Input controlado por el estado de React.

2. ¿Deberíamos esperar a almacenar las respuestas de los usuarios del formulario en el state cuando envían el formulario O debemos actualizar el state con sus respuestas tan pronto como las ingresen? ¿Por qué?
    - Debemos actualizar el state a medida que ingresan las respuestas, ya que esto permite realizar validaciones en tiempo real y mantener el control sobre los datos ingresados.

3. ¿Cómo utilizamos target lo que el usuario está introduciendo si tenemos un event handler en un campo de input?
    - Accedemos al valor con event.target.value.

## The Conditional (Ternary) Operator Explained

1. ¿Por qué utilizaríamos un operador ternario?
    - Simplifica if-else en una sola línea.

2. Vuelve a escribir la siguiente declaración utilizando una declaración ternaria:

    - console.log(x === y ? true : false);

### Fuentes

- [How to use Forms in React](https://www.robinwieruch.de/react-form/)
- [JavaScript — The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
