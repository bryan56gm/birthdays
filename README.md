# Proyecto de Almacenamiento de Cumpleaños con Flask

Este es un proyecto de aplicación web simple para almacenar y gestionar cumpleaños usando Flask y una base de datos SQLite. La aplicación permite a los usuarios añadir, ver y eliminar cumpleaños mediante un formulario.

## Descripción

La aplicación permite a los usuarios:

- **Añadir cumpleaños**: Introducir el nombre y la fecha de cumpleaños de una persona.
- **Ver cumpleaños**: Consultar una lista de todos los cumpleaños almacenados mediante una tabla.

## Requisitos

- Python 3.6 o superior
- `virtualenv` para la creación de entornos virtuales

## Instalación y Ejecución

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/bryan56gm/birthdays.git
   
2. **Muevete a la carpeta del proyecto:**
   ```bash
   cd birthdays

3. **Crea un entorno virtual:**
   ```bash
   python -m venv venv

4. **Activa el entorno virtual en Windows:**
   ```bash
   source venv/Scripts/activate
   
5. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   
6. **Ejecuta la aplicación Flask:**
   ```bash
   flask run
   
7. **La aplicación estará disponible en:**
   [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

![Flask Birthdays](https://raw.githubusercontent.com/bryan56gm/birthdays/main/preview.jpg)
