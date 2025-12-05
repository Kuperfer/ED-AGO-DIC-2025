===== Simulación de atención al cliente en bancos =====

Este programa en C simula un sistema de atención de clientes de un banco en tres colas paralelas. Cada cliente llega con un tiempo de llegada y un número de transacciones que tarda en procesar. Los clientes se asignan aleatoriamente a una de las colas, que luego son atendidas simultáneamente por hilos independientes.


===== Archivos =====
    § main.c: Archivo fuente principal que contiene toda la lógica.


===== Requisitos =====
    $ Compilador de C compatible con funciones matemáticas estándar (como gcc, clang, o MinGW).


===== Compilación ===== (ojo, se tiene que compilar el/los comandos con una nueva terminal, y asegurarse de estar dentro de la carpeta del ADA).
    § Linux / macOS
        gcc main.c -o banco

    § Windows
        gcc main.c -o banco
===== Ejecución =====
    § Linux / macOS
        ./banco

    § Windows
        ./banco

===== Notas =====
    § Los tiempos de llegada y duración de transacciones son generados aleatoriamente en cada ejecución.
    $ Puedes modificar la constante MAX_CLIENTES y UM_COLAS dentro del archivo main.c para ajustar la cantidad de clientes simulados.

===== Contacto: Equipo 09 =====
§ C. Ku Perez Fernando Alonso (Estudiante de la LIC)
        a24216429@alumnos.uady.mx
