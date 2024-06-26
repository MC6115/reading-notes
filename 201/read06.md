# Clase 06: Lectura

## Conceptos básicos de los objetos JavaScript

1. ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?

    - Un objeto es como una caja que guarda diferentes cosas relacionadas, como tus juguetes en una caja.

2. ¿Cuáles son algunas de las ventajas de crear objetos literales?

    - Son fáciles de crear, entender y mantener. Permiten agrupar datos relacionados de forma clara.

3. ¿En qué se diferencian los objetos de los arrays?

    - Los objetos almacenan datos como pares clave-valor, mientras que los arrays almacenan datos en una lista ordenada.

4. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.

    - Cuando el nombre de la propiedad contiene espacios o caracteres especiales, o es una variable:

    ```js
    const obj = {'property name': 'value'};
    console.log(obj['property name']);
    ```

5. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?

    - JavaScript puede utilizar el DOM para acceder y manipular el contenido, estructura y estilo de una página web.

```js
    const dog = {
        name: 'Spot',
        age: 2,
        color: 'white with black spots',
        humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
        }
    }
```

## Introducción al DOM

1. ¿Qué es el DOM?

    - El DOM (Document Object Model) es una representación estructurada de un documento HTML que permite a los lenguajes de programación interactuar con él.

2. Describe brevemente la relación entre el DOM y JavaScript.

    - JavaScript puede utilizar el DOM para acceder y manipular el contenido, estructura y estilo de una página web.

### Fuentes

- [Conceptos básicos de los objetos JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/Basics)
- [Introducción al DOM](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction)
