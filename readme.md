
# Hoy vamos a hacer actividad en Python en un día como programadores:

 1.⁠ ⁠Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Windows


 2.⁠ ⁠Creamos una carpeta o directorio: 

    ⁠ bash
    mkdir python-final
     ⁠

 3.⁠ ⁠Entramos en ella: 

    ⁠ bash
    cd python-final
     ⁠

 4.⁠ ⁠Iniciamos el repositorio:

    ⁠ bash
    git init
     ⁠

 5.⁠ ⁠Creamos un archivo:

    ⁠ bash
    touch finales.py
     ⁠

 6.⁠ ⁠Abrimos VSC:

    ⁠ bash
    code .
     ⁠

 7.⁠ ⁠En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

    ⁠ bash
    python -V
    python3 -V
     ⁠

 8.⁠ ⁠Creamos el entorno virtual en Python:

    ⁠ bash
    python3 -m venv venv # Creamos el entorno virtual
     ⁠

 9.⁠ ⁠Activamos el entorno virtual:

    ⁠ bash
    source venv/bin/activate # Activamos el entorno virtual en Linux
    venv/scripts/activate # En Windows
     ⁠

10.⁠ ⁠Hacemos actualización del pip de Python:

    ⁠ bash
    python3 -m pip install --upgrade pip # Actualizamos el pip
     ⁠

11.⁠ ⁠Investigar ¿Qué es el pip y por qué lo actualizamos?

12.⁠ ⁠Hacer el primer commit de este trabajo y unirlo al repositorio remoto.



# Actividad en Python: Configuración de Entorno de Desarrollo

## Introducción

En esta guía, configuraremos un entorno de desarrollo en Python. Este proceso incluye la creación de un directorio, la inicialización de un repositorio Git, la creación de un entorno virtual y la actualización de `pip`. Siguiendo estos pasos, estarás preparado para comenzar a programar en Python de manera eficiente.

## Pasos para Configurar el Entorno

### 1. Abrir la Terminal

Abre la terminal de Git Bash (en Windows) o la terminal en Linux. En Windows, asegúrate de ejecutar Git Bash como administrador para tener los permisos necesarios.

### 2. Crear un Directorio

Crea una nueva carpeta llamada `python-final` donde almacenarás tu proyecto. Esto se logra con el siguiente comando:

```bash
mkdir python-final
