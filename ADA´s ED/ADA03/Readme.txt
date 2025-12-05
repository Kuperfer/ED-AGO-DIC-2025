===== Implementación de lista de Movies con Listas  =====

Este programa en C implementa una lista de "Movies" con listas.

===== Archivos =====
    - csv_handler.c y csv_handler.h: Permiten manipular Movies.csv (eliminar info, actualizar los campos, insercción de nuevas peliculas, etc).

    - doubly_linked_list.c: Contiene la lógica de toda una lista doblemente enlazada y su algoritmo de recorrido es final, por ello, agrega un nodo al final.

    - doubly_linked_list.h: Contiene los prototipos y definicion de variables para crear estructuras películas (Movie) y para la estructura de datos lista doblemente enlazada de películas.

    - main.c: Menú del programa que contiene las funciones principales.

    - movie_utils.c: Funciones y procedimientos para un struct Movie.

    - Movies.csv: Lista de películas.


===== Requisitos =====
    $ Compilador de C compatible con funciones matemáticas estándar (como gcc, clang, o MinGW).


===== Compilación ===== (ojo, se tiene que compilar el/los comandos con una nueva terminal, y asegurarse de estar dentro de la carpeta del ADA).
    § Linux / macOS
        

    § Windows
        gcc main.c movie_utils.c doubly_linked_list.c csv_handler.c -o proyecto
===== Ejecución =====
    § Linux / macOS
        

    § Windows
        ./proyecto

===== Notas =====
    § Este programa solo se a testeado en Windows.

===== Contacto: Equipo 09 =====
§ C. Ku Perez Fernando Alonso (Estudiante de la LIC)
        a24216429@alumnos.uady.mx