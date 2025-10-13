# Clase N°2: Desarrollo de un Chatbot con Flask

Este documento detalla los pasos esenciales para configurar el entorno de desarrollo del proyecto de Chatbot utilizando el framework **Flask**.

### Pasos para crear el proyecto

Sigue las siguientes instrucciones en tu terminal para estructurar la carpeta e inicializar el entorno de trabajo.

1.  **Creación del Directorio Principal**

    Crea la carpeta para tu proyecto.

    ```bash
    mkdir Chatbot
    ```

2.  **Acceso al Directorio**

    Navega hacia la carpeta recién creada.

    ```bash
    cd Chatbot
    ```

3.  **Crea el entorno virtual**

    Crea un entorno virtual para aislar las dependencias del proyecto.

    ```bash
    python -m venv env
    ```

4.  **Activación del Entorno Virtual**

    El método de activación depende de tu sistema operativo:

    **Opción A: Sistemas Linux/macOS**

    ```bash
    source ./env/bin/activate
    ```

    **Opción B: Sistemas Windows**

    ```bash
    ./env/Scripts/activate
    ```

    **Nota para PowerShell en Windows**: Si tu sistema restringe la ejecución de scripts, podrías necesitar cambiar la política de ejecución. Ejecuta el siguiente comando en la terminal con permisos de Administrador (solo si es necesario):

    ```bash
    Set-ExecutionPolicy-ExecutionPolicy RemotSigned Scope CurrentUser
    ```

5.  **Instalación de Dependencias**

    Con el entorno virtual activado, instala Flask, la dependencia principal requerida hasta ahora para el proyecto.

    ```bash
    pip install flask
    ```
