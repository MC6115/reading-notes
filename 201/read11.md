# Clase 11: Lectura

## Contenido de audio y video

1. Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.

    - La capacidad de utilizar video y audio en la web ha evolucionado significativamente desde principios de los 2000. Inicialmente, los navegadores solo admitían formatos como GIF animados y clips de audio básicos. Con HTML5 y el soporte generalizado de navegadores modernos, se introdujo `<video>` y `<audio>`, permitiendo la reproducción sin plugins. Esto ha integrado video y audio de alta calidad en las aplicaciones web, mejorando las experiencias de usuario.

2. Describe el uso de los atributos src y controls en el elemento `<video>`.

    - El atributo src especifica la URL del archivo de video que se va a reproducir.

    - El atributo controls muestra controles de reproducción estándar para el video, como botones de reproducción/pausa, volumen y barra de progreso.

3. ¿Por qué es importante tener contenido de respaldo en el elemento `<video>`?

    - Es importante tener contenido de respaldo en el elemento `<video>` para asegurar que los usuarios puedan acceder al contenido multimedia incluso si no pueden reproducir el video principal debido a problemas de formato, compatibilidad del navegador o conexión a internet. Esto se logra incluyendo un enlace a un archivo de video alternativo o proporcionando subtítulos descriptivos.

4. Escribe una historia corta en donde `<audio>` y `<video>` son personajes.

    - En un mundo donde `<audio>` y `<video>` eran personajes mágicos, `<audio>` era conocido como Melodio, capaz de encantar a todos con sus sonidos encantadores. Mientras tanto, `<video>`, apodado Visio, podía transportar a las personas a tierras lejanas con sus imágenes vividas. Juntos, Melodio y Visio formaron un dúo imparable que cautivaba a audiencias de todas partes del mundo web.

5. ¿En qué se diferencia el layout Grid del Flex?

    - Grid: Permite un diseño bidimensional, ideal para estructuras de diseño más complejas donde se necesita control tanto en filas como en columnas.
    - Flex: Proporciona un diseño unidimensional, útil para disposiciones más simples donde el contenido fluye en una dirección (horizontal o vertical).

6. Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.

    - Grid container: Es el elemento padre que contiene elementos grid.
    - Grid item: Son los elementos hijos directos de un contenedor grid que se colocan dentro de las filas y columnas definidas.
    - Grid line: Son las líneas divisorias que definen los límites de las filas y columnas en un grid.

## Imágenes Responsivas

1. Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?

    - Además de mejorar la apariencia visual en diferentes tamaños de pantalla, los desarrolladores deberían hacer imágenes responsivas para optimizar la carga y el uso de datos, adaptarlas a dispositivos diversos y mejorar el SEO conforme a las prácticas de Google.

2. Define los siguientes atributos de `<img>`: `srcset` y `sizes`. Escribe un ejemplo de cómo se usan.

    - **srcset**: Especifica una lista de imágenes junto con los tamaños de pantalla a los que se aplican. El navegador selecciona la imagen adecuada según la resolución y densidad de píxeles del dispositivo.
    - **sizes**: Especifica el tamaño del elemento `<img>` en diferentes puntos de ruptura de pantalla. Define cuánto espacio ocupará la imagen en relación con el ancho del contenedor.

    ```html
    <img src="imagen-pequena.jpg" 
        srcset="imagen-grande.jpg 2x, imagen-mediana.jpg 1.5x"
        sizes="(max-width: 600px) 100vw, (max-width: 1200px) 50vw, 800px"
        alt="Descripción de la imagen">
     ```

3. ¿Cómo es que `srcset` es más útil para las imágenes responsivas que CSS o JavaScript?

    - Adaptación automática: `srcset` permite al navegador elegir automáticamente la imagen más adecuada según la resolución del dispositivo, mientras que CSS o - - JavaScript requieren configuraciones manuales.
    - Rendimiento: Utilizar srcset optimiza el rendimiento al cargar solo la imagen necesaria, reduciendo el uso de ancho de banda y mejorando los tiempos de carga de la página.
    - Accesibilidad: srcset es compatible con tecnologías de asistencia y motores de búsqueda, lo que mejora la accesibilidad y el SEO de la página web.

### Fuentes

- [Contenido de audio y video](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [A Complete Guide to CSS Grid](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [Imágenes adaptables](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
