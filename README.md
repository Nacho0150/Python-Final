# Clase 11 Actividad en Python

> Hoy vamos a hacer actividad en Python en un día como programadores:

1. **Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window**

2. **Creamos una carpeta o directorio:**

    ```sh
    mkdir python-final
    ```
    
3. **Entramos en ella:**

   ```sh
   cd python-final
   ```

4. **Iniciamos el repositorio:**

   ```sh
   git init
   ```

5. **Creamos un archivo:**

   ```sh
   touch finales.py
   ```

6. **Abrimos VSC:**

   ```sh
   code .
   ```

7. **En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:**

   ```sh
   python -V

   python3 -V
   ```

8. **Creamos el entorno virtual en Python:**

   ```sh
   python3 -m venv venv #Creamos el entorno virtual
   ```

9. **Activamos el entorno virtual:**

   ```sh
   source venv/bin/activate #Activamos el entorno virtual en Linux

   venv/scripts/activate #En windows
   ```

10. **Hacemos actualización del pip de Python**

    ```sh
    python3 -m pip install --upgrade pip #Actualizamos el pip
    ```

11. **Investigar ¿Qué es el pip y porque lo actualizamos?**

    'pip' es el sistema de gestión de paquetes para Python. Permite instalar y gestionar bibliotecas y paquetes adicionales que no están incluidos 
    en la biblioteca estándar de Python. Con pip, puedes descargar e instalar paquetes desde el Python Package Index (PyPI), que es un repositorio 
    de software para el lenguaje de programación Python.

    **¿Por qué actualizamos pip?**

    1. **Mejoras y nuevas características**: Las nuevas versiones de pip a menudo incluyen mejoras en el rendimiento, nuevas características y mejoras en la usabilidad.
    2. **Seguridad**: Actualizar pip ayuda a garantizar que se estén utilizando versiones con los últimos parches de seguridad. Esto es crucial para evitar
       vulnerabilidades que podrían ser explotadas.
    4. **Compatibilidad**: Las nuevas versiones de pip a menudo incluyen soporte para nuevas versiones de Python y para nuevos estándares y prácticas
       en el desarrollo de software. Esto asegura que pip siga siendo compatible con la infraestructura de desarrollo más reciente.
    6. **Corrección de errores**: Actualizar pip puede corregir errores y problemas conocidos de versiones anteriores, proporcionando una experiencia más estable y confiable.  

12. **Hacer al primer commit de este trabajo y unirlo al repositorio remoto.**

13. **Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos,
    y las respuesta del punto 11 de más arriba.**
