## Blog en Django
Este es un blog simple desarrollado con Django que permite a los usuarios autenticados crear, editar y eliminar publicaciones. 
Los editores tienen permisos especiales para gestionar el contenido del blog a través de la interfaz de administración de Django.

Podéis clonar el repositorio e instalar el entorno virtual así, se requiere pipenv:

git clone https://github.com/hektorprofe/tutorial-django-blog.git
cd tutorial-django-blog/
pipenv install -r requirements.txt
Para poner en marcha el proyecto:

pipenv run python manage.py runserver
El usuario del administrador es admin con contraseña 1234, podéis crear uno al gusto con:

pipenv run python manage.py createsuperuser
