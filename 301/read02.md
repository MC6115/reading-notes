# Lecturas: State y Props

## React lifecycle

1. Según el diagrama, ¿qué sucede primero, el ‘render’ o el ‘componentDidMount’?

    - El render ocurre primero. Después del render, se ejecuta el método componentDidMount.

2. ¿Qué es lo primero que sucede en el ciclo de vida de React?

    - Lo primero que sucede es la llamada al constructor del componente, si existe. Aquí es donde se inicializa el state y se enlazan métodos.

3. Coloca las siguientes cosas en el orden en que suceden: componentDidMount, render, constructor, componentWillUnmount, React Updates

    1. constructor
    2. render
    3. componentDidMount
    4. React Updates
    5. componentWillUnmount

4. ¿Qué hace el componentDidMount?

    - El método componentDidMount se ejecuta una vez que el componente ha sido montado en el DOM. Es útil para realizar operaciones como llamadas a APIs, inicializar suscripciones o cualquier configuración que requiera acceso al DOM.

## React State Vs Props

1. ¿Qué tipo de cosas puedes enviar mediante props?

    - Puedes enviar cualquier tipo de dato mediante props, como:

        - Strings
        - Números
        - Objetos
        - Arrays
        - Funciones
        - Componentes de React

2. ¿Cuál es la mayor diferencia entre props y state?

    - La principal diferencia es que las props son inmutables, es decir, son datos que se pasan de un componente padre a un componente hijo y no pueden ser modificadas por el componente hijo. El state, en cambio, es mutable y puede ser modificado dentro del propio componente para controlar su comportamiento y renderización.

3. ¿Cuándo volvemos a renderizar nuestra aplicación?

    - La aplicación se vuelve a renderizar cuando el state o las props cambian. Un cambio en cualquiera de estos dos elementos provoca una actualización del componente.

4. ¿Cuáles son algunos ejemplos de cosas que podríamos almacenar en el state?

    - Algunos ejemplos de cosas que podríamos almacenar en el state son:

        - Datos de formularios (como inputs)
        - Contadores o valores numéricos que cambian dinámicamente
        - Información de usuario como nombres o preferencias
        - Estado de una solicitud a una API (cargando, error, datos recibidos)

### Fuentes

- [React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
- [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
