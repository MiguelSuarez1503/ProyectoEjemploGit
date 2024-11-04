# Título de la Tarea: Programa Hola Mundo en Java

## Descripción
Este programa imprime el mensaje "Hola Git" en la consola. El objetivo de la tarea es entender el funcionamiento de Git y de Github

## Instrucciones de uso
Para ejecutar el programa `HolaMundo.java`, sigue estos pasos:

1. Tener instalado Java en tu computadora.
2. Abrir una terminal y navegar hasta la carpeta donde se encuentra `HolaMundo.java`.
3. Compilar el programa con el siguiente comando: javac HolaMundo.java
4. Ejecutar el programa con el comando: java HolaMundo

### Comandos utilizados 
1. git init - Inicializa el repositorio.
2. git add HolaMundo.java - Agrega el archivo HolaMundo.java al área de preparación.
3. git commit -m "Primer commit" - Realiza el primer commit.
4. git add .gitignore - Agrega el archivo .gitignore.
5. git commit -m "Se agregó el archivo .gitignore" - Realiza el segundo commit.
6. git add debug.log - Agrega el archivo debug.log.
7. git commit -m "Se actualizó el mensaje en HolaMundo.java" - Realiza el tercer commit.
8. git status - Verifica el estado de los archivos en el repositorio.

#### Notas sobre el archivo .gitignore

_Se creó el archivo .gitignore para evitar que ciertos archivos, en este caso, aquellos con la extensión .log, sean rastreados y subidos al repositorio. Esto es útil para mantener el repositorio limpio y evitar subir archivos que son temporales o que no son necesarios para el funcionamiento del programa._

##### ¿Qué debe mostrar el programa al ejecutarlo  y cómo verificar que debug.log no se subió?

El programa al ejecutarlo debe mostrar en pantalla "Hola Git"
Para verificar que debug.log no se subió se puede ejecutar el comando git status y debug.log no debería aparecer 

   
