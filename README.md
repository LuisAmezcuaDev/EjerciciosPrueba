# Ejercicios 
Se creó un script por cada ejercicio que se realizo en la prueba. Para el script llamado "contarPalabras.py" se creo el archivo de texto "ejemplo.txt" para poder probar su funcionalidad

# Proyecto de API CRUD para Tareas en Django

API de Django que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en un recurso llamado "Tareas".

## Requisitos

Antes de comenzar, asegúrate de tener los siguientes requisitos instalados en tu máquina:

- [Python 3.8+](https://www.python.org/)
- [Django](https://www.djangoproject.com/) 5.1.7
- [Django REST Framework](https://www.django-rest-framework.org/)
- [pip](https://pip.pypa.io/en/stable/)

## Instalación

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. **Clona el repositorio**

   Primero, clona el repositorio en tu máquina local utilizando Git:
   
   ```bash
   git clone https://github.com/LuisAmezcuaDev/EjerciciosPrueba

2. **Crea un entorno virtual**

    python -m venv .venv
    Luego activa el entorno 

    .\.venv\Scripts\activate

3. **Aplica las migraciones**
    python manage.py migrate

4. **Crea un super usuario**
    python manage.py createsuperuser

5. **Corre el servidor**
    python manage.py runserver

5. **Uso de la apl**
    Es necesario usar una herramienta que permita realizar pruebas con la api como Postman o thunder client en el editor de Visual Studio. Las direcciones son las siguientes

   - GET: http://127.0.0.1:8000/api/tareas/
   - GET by ID: http://127.0.0.1:8000/api/tareas/{id}
   - PUSH: http://127.0.0.1:8000/api/tareas/
    Estructura del json {
        "nombre": "Tarea de prueba",
        "descripcion": "Descripción de la tarea",
        "completada": false
    }
   - PUT: http://127.0.0.1:8000/api/tareas/{id a editar}/
   
    Estructura del json {
   
        "nombre": "Tarea de prueba",
   
        "descripcion": "Descripción de la tarea",
   
        "completada": false
   
   }
   - DELETE: http://127.0.0.1:8000/api/tareas/{id campo a eliminar}/

