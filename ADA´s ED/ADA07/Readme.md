# ADA07_E09

## Descripción
Este repositorio contiene el código fuente y el Makefile necesarios para compilar y ejecutar la práctica **ADA07_E09** (del cual consistía en 2 problemas).  
El Makefile automatiza la compilación, ejecución y limpieza de los artefactos generados.

## Problema 1; Registro de Estudiantes con Colisiones Controladas:
Consiste en sistema para universidades que almacene estudiantes usando su matrícula como clave. La 
clave está compuesta por solo números de máximo 6 dígitos. Los estudiantes deben ser recuperados 
eficientemente, incluso con colisiones.

## Problema 2; Tabla de símbolos en un compilador:
Un compilador o intérprete, en el que se necesita mantener un registro de los identificadores (variables, 
funciones, etc.) y sus atributos (tipo, valor, ámbito, etc.). 

La clave es el nombre del identificador (string) y el valor es una estructura que contiene los 
atributos. La tabla hash permite una búsqueda rápida para verificar si un identificador ya ha sido declarado y 
para acceder a sus atributos.

## Contacto:
- **C. Ku Perez Fernando Alonso** (Estudiante de la LIC)  
  Correo: `a24216429@alumnos.uady.mx`

## Requisitos
- MSYS2 con shell **MINGW64**.
- Herramienta `make` disponible en el entorno **MINGW64**.

## Uso rápido en Microsoft Windows
1. Abrir el shell **MSYS2 MINGW64**.
2. Entrar al directorio del proyecto:
    ```bash
    cd ADA_07
    ```
3. Ejecutar el Makefile:
    ```bash
    make
    ```
   > Este comando compila ambos programas y genera los ejecutables en la carpeta `bin/`.

## Targets disponibles
- `make` — objetivo por defecto: compila y ejecuta el proyecto.
- `make clean` — elimina archivos generados (binarios, objetos, etc.).

## Notas
- Es importante usar el shell **MINGW64** para asegurar que las rutas y herramientas funcionen correctamente.
- Asegúrate de que `make` esté correctamente instalado y accesible desde el entorno MSYS2.
