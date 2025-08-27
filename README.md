## **📚 Catálogo de Cursos Online (Django)**

Mini proyecto CRUD con Django: curso, duración, plataforma y dificultad.
Metodologías aplicadas: Scrum + XP, repositorio en GitHub y CI con GitHub Actions.

## **🚀 Descripción**


-Este proyecto permite gestionar un catálogo de cursos online de manera interactiva. Los usuarios pueden:

-Crear nuevos cursos con sus datos: nombre, duración, plataforma y dificultad.

-Leer o consultar todos los cursos existentes.

-Actualizar información de cursos existentes.

-Eliminar cursos que ya no sean necesarios.

-El objetivo principal es aprender a aplicar Python con Django en un proyecto CRUD, trabajando en equipo bajo metodologías ágiles como Scrum, usando control de versiones con GitHub y configurando integración continua.


## **👥 Integrantes y Roles**

| Rol           | Integrante      | Función                                                                   |
|---------------|-----------------|-------------------------------------------------------------------------  |
| Scrum Master  | Williams Galindo| Dirige el proyecto, asigna tareas y asegura que todos cumplan su rol.     |
| Product Owner | Thory Vera      | Coordina funcionalidades, prioriza historias de usuario y apoya en Trello.|
| Developer 1   | Andres Salinas  | Creación y mejora del código, pruebas, soporte en integración.            |
| Developer 2   | Ayrton Yactayo  | Apoyo en desarrollo del código y organización de tareas.                  |
| Developer 3   | Josue Ochoa     | Implementación y prueba del código, colaboración en funcionalidades.      |


## **🚀 Requisitos**
- Python 3.11 (o 3.10)
- pip

  
## **🖥️ Lenguajes utilizados**

| Lenguaje | Porcentaje |
|----------|------------|
| Python   | 66.9%      |
| HTML     | 33.1%      |

## **🔧 Instalación y ejecución**



2️⃣ Crear entorno virtual

-Instalar virtualenv :

pip install virtualenv


-Crear el entorno virtual dentro de la carpeta:

virtualenv venv


-Activar el entorno virtual:

.\venv\Scripts\activate

3️⃣ Abrir el proyecto en Visual Studio Code

Arrastra la carpeta catalogo_cursos_integral a Visual Studio Code
(o abre VS Code → File > Open Folder → selecciona la carpeta).

4️⃣ Instalar Django

-En la terminal de Visual Studio Code (con el entorno activado):

pip install django


Si tienes el archivo requirements.txt:

pip install -r requirements.txt

5️⃣ Migrar la base de datos
python manage.py migrate

6️⃣ Ejecutar el servidor
python manage.py runserver


En la terminal aparecerá un mensaje similar a:

Starting development server at http://127.0.0.1:8000/


👉 Por defecto será: http://127.0.0.1:8000


 ## **🧪 Tests**
```bash
python manage.py test
```


## **🤖 CI con GitHub Actions**
Workflow en `.github/workflows/django.yml`: instala deps, migra y corre tests en cada push/PR a `main`.

Licencia

Indicar si el proyecto es libre (ej. MIT, GPL) o de uso interno.

Ejemplo: ## 📜 Licencia → MIT License.

Guía de Contribución

Si más personas van a colaborar: pasos para hacer pull requests, ramas, estilo de código.

Ejemplo: ## 🤝 Contribución.

Uso del Proyecto (Ejemplo práctico)

Un ejemplo de cómo se ve el CRUD (capturas o un GIF).

Ejemplo de comandos para crear un curso desde el admin o desde el frontend.
