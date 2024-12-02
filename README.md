# M6-L7-Django-Formularios
Educativo y de Aprendizaje Personal

---

## Tabla de Contenidos
- [Requisitos](#requisitos)
- [Configuración del Entorno](#configuración-del-entorno)
- [Activación del Entorno](#Activación-del-Entorno)
- [Configuración Inicial](#configuración-inicial)
- [Pasos del Proyecto](#pasos-del-proyecto)
  - [Configuración del Proyecto](#configuración-del-proyecto)
  - [Creación del Superusuario](#Creación-del-Superusuario)
  - [Creación de Vistas y Modelos](#creación-de-vistas-y-modelos)

---
## Requisitos

- Python 3.9 o superior
- Django 4.0 o superior

---
## Configuración del Entorno

1. Crear el entorno virtual:
   ```bash
   python -m venv venv

## Activación del Entorno

2. Activar el entorno virtual:
    ### Windows
    ```bash
    venv\Scripts\activate

## Configuración Inicial
## Instalar Django y Guardar dependencias

3. Intalación Django
    ```bash
    pip install django

4. Instalamos la actualizacion de pip
    ```bash
    python.exe -m pip install --upgrade pip

## Guardar las dependencias
5. Instalación dependencias
    ```bash
   pip freeze > requirements.txt

## Pasos del Proyecto
6. Crear el Proyecto
    ```bash
    django-admin startproject formulario

7. Ingresar al directorio del Proyecto
    ```bash
    cd formulario
8. Creamos la Aplicación 
    ```bash
    python manage.py startapp froms_app

## Configuración del Proyecto

9. Hacemos Migraciones para que cree las tablas por defecto que tiene django y creando el db.sqlite3
   ```bash 
   python manage.py migrate


10. Conectar el proyecto con la aplicación: Agregar '', en la lista INSTALLED_APPS dentro del archivo formulario/settings.py
    ```bash

    INSTALLED_APPS = [
        'django.contrib.admin',
        'django.contrib.auth',
        'django.contrib.contenttypes',
        'django.contrib.sessions',
        'django.contrib.messages',
        'django.contrib.staticfiles',
        'form'
    ]


11.

12.

13.

14.

15.

16.

17.

18.

19.



