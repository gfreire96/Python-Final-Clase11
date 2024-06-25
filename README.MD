Pip es el administrador de paquetes de Python que permite instalar, actualizar y desinstalar librerías y paquetes de Python. Es una herramienta fundamental cuando se trabaja con Python.

Cuando se crea un entorno virtual (venv), el objetivo es tener un ambiente aislado con sus propias dependencias. Sin embargo, el pip que viene instalado por defecto en el entorno virtual puede estar desactualizado. Por eso, es recomendable actualizar pip después de crear el entorno virtual:

## Activar el entorno virtual:
- En Windows: `env\Scripts\activate`
- En Linux/Mac: `source env/bin/activate`

## Actualizar pip:
`python -m pip install --upgrade pip`

Actualizar pip en el entorno virtual asegura que se tenga la última versión del administrador de paquetes. Esto es importante porque:

- La última versión de pip suele tener mejoras de rendimiento y corrección de bugs.
- Algunas librerías pueden requerir una versión mínima de pip para poder instalarse correctamente.

En resumen, actualizar pip después de crear un entorno virtual es una buena práctica que garantiza un mejor manejo de las dependencias del proyecto.

-------------------------------------------------------------------------------

Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 
   `mkdir python-final`

3. Entramos en ella: 
   `cd python-final`

4. Iniciamos el repositorio:
   `git init`

5. Creamos un archivo:
   `touch finales.py`

6. Abrimos VSC:
   `code .`

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
   `python -V`
   `python3 -V`

8. Creamos el entorno virtual en Python:
   `python3 -m venv venv #Creamos el entorno virtual`

9. Activamos el entorno virtual:
   `source venv/bin/activate #Activamos el entorno virtual en Linux`
   `venv/scripts/activate #En windows`

10. Hacemos actualización del pip de Python
    `python3 -m pip install --upgrade pip #Actualizamos el pip`

11. Investigar ¿Qué es el pip y porque lo actualizamos?
    Pip es el administrador de paquetes de Python que permite instalar, actualizar y desinstalar librerías y paquetes de Python. Es una herramienta fundamental cuando se trabaja con Python.
    Actualizamos pip porque el que viene instalado por defecto en el entorno virtual puede estar desactualizado. La última versión de pip suele tener mejoras de rendimiento y corrección de bugs, y algunas librerías pueden requerir una versión mínima de pip para poder instalarse correctamente.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
