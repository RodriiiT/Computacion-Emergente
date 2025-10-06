# Computación Emergente

Este repositorio está dedicado a la materia de **Computación Emergente**. Aquí se publicarán las prácticas individuales, las clases, las tareas asignadas y las prácticas evaluadas, entre otros recursos relacionados con el curso.

**Estudiante:** Rodrigo Torres  
**Semestre:** 9no Semestre  (Electiva III)


#Clase nº2

### Pasos para crear el proyecto

1. Crear la carpeta, para ello usa el comando de **mkdir** y luego agrega el nombre de la carpeta
   ```bash
   mkdir Chatbot
   ```
2. Navega hacia la carpeta con el siguiente comando
   ```bash
   cd Chatbot
   ```
3. Crea el entorno virtual
   ```bash
   python -m venv env
   ```
4. Despuès de crear el entorno virtual, tendràs que activar el entorno y para ello hay dos vertientes. La primera opciòn es si tienes **Linux** ejecuta lo siguiente
  ```bash
  source ./env/bin/activate
  ```
  La segunda opciòn es si estàs en Windows, entonces ejecuta lo siguiente:
  ```bash
  ./env/Scripts/activate
  ```
  _En caso de querer ejecutarlo con todos los permisos, agregaga ".ps1" al final pero no si antes ejecutar el siguiente comando en la terminal:_
  ```bash
  Set-ExecutionPolicy-ExecutionPolicy RemotSigned Scope CurrentUser
  ```
5. Luego de todo al fin ejecuta este comando para tener **hasta ahora** todas las dependecias necesarias para el proyecto
  ```bash
  pip install flask
  ```
