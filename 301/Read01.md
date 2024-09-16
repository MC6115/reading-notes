# Lecturas: Introducción a React y los Componentes

## Component-Based Architecture

1. ¿Qué es un “componente”?

    - Un componente en React es una pieza reutilizable e independiente de la interfaz de usuario. Cada componente representa una parte específica de la UI (por ejemplo, un botón, un formulario o un menú) y puede tener su propio estado y lógica.

2. ¿Cuáles son las características de un componente?

    - Las principales características de un componente son:
        - Reutilizable: Se puede usar en múltiples lugares de la aplicación.
        - Independiente: Tiene su propia lógica y manejo del estado.
        - Composición: Los componentes pueden estar formados por otros componentes más pequeños.
        - Encapsulamiento: La lógica y la representación están aisladas dentro del componente.
        - Declarativo: Los componentes describen cómo debería verse la interfaz en un estado específico.

3. ¿Cuáles son las ventajas de utilizar una arquitectura basada en componentes?

    - Las ventajas incluyen:
        - Reutilización de código: Los componentes se pueden reutilizar en diferentes partes de la aplicación.
        - Mantenibilidad: Al dividir la aplicación en partes más pequeñas, es más fácil de mantener y actualizar.
        - Escalabilidad: Facilita el crecimiento de la aplicación al agregar nuevos componentes o modificar los existentes sin afectar el resto del sistema.
        - Aislamiento: Cada componente maneja su lógica y estado, lo que permite un desarrollo más modular.

## What is Props and How to Use it in React

1. ¿Qué significa “props”?

    - Props es una abreviatura de "properties" y son los datos que se pasan de un componente padre a un componente hijo. Los props permiten que los componentes sean dinámicos y reutilizables al recibir valores desde el exterior.

2. ¿Cómo se utilizan los props en React?

    - Los props se pasan como atributos HTML en un componente y se acceden dentro del componente hijo a través de this.props en los componentes de clase, o directamente como argumentos en los componentes funcionales.

3. ¿Cuál es el flujo de los props?

    - El flujo de los props es unidireccional, es decir, los datos fluyen de los componentes padres hacia los componentes hijos. Los componentes hijos no pueden modificar los props que reciben, lo que asegura que el flujo de datos sea controlado y predecible.

### Fuentes

- [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
- [How to Use Props in React.js](https://www.freecodecamp.org/news/how-to-use-props-in-reactjs/)
