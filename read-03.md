# Read 03: Versionamiento local y remoto

## Version control
Un sistema que te permite regresar un archivo o multiples archivos a un estado en el cual estubieron antes, esto permite: 
- Monitorear cambios
- Ver quien hizo un cambio
- Y comparar cambios hechos por distintas personas.

Esto permite correjir y manejar errores en un archivo.

## Typos de Version control
Existen 3 typos de version control: Local version control, Centralized version control(**CVCS**) y Distributed version control(**DVCS**). Y se diferencian de uno a otro de la siguente forma.
1. Local version control
- Una de las formas mas antiguas de Version control, usa el disco duro de tu computadora para guardar los cambios a los archivos
2. Centralized version control (**CVCS**)
- De la misma forma que funciona el local version control **CVCS** mantiene todos los cambios hechos en un servidor central, accesible por todas las personas trabajando en el projecto a traves de varios metodos, haciendo la colaboracion de varias personas en un mismo projecto mucho mas cencilla
3. Distributed version control (**DVCS**)
- Este metodo de version control soluciona un problema fundamental de los **CVCS**, lo cual es que si el servidor central llega a fallar los colaboradores no pueden trabajar, cambiar o guardar una version nueva de los archivos de sus compañeros
- **DVCS** permite a los clientes crear repositorios que muestran la misma informacion que el servidor y funciona para reemplazar cualquier informacion que se haya perdido,
- esto permite que programadores colaboren juntos en un solo projecto mas eficazmente.

## Git remote

Para colaborar en proyectos de Git, debes interactuar con repositorios remotos,
que son versiones de un proyecto que residen en línea. Puedes trabajar con varios repositorios,
para los cuales puedes tener privilegios de edicion o solo de observar. Y se pueden utilizar repositorios
remotos para enviar información y extraer datos.
El comando 'git remote' te permite ver los nombres de los repositorios remotos y te da su indicado url, permitiento accederlos facilmente.

### Responde:
1. ¿Qué es el control de versiones?
  - Un sistema que te permite regresar un archivo o multiples archivos a un estado en el cual estubieron antes.
2. ¿Qué es “clone” en Git?
  - Permite *clonar* un repositorio que existe en un servidor o un  url a tu maquina, esto incluye su historial de versiones
3. ¿Cuál es el comando para rastrear y preparar archivos?
- El comando para añadir cambios realizados al area de preparacion es 'git add'
4. ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
  - 'git commit'. Este comando guarda los cambios que han sido previamente añadidos al área de preparación utilizando el comando 'git add'.
5. ¿Cuál es el comando para enviar los archivos modificados a Github?
- Para enviar archivos modificados a github usas el comando 'git push'

