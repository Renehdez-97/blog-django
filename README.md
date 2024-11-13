## Poner en marcha el proyecto

1. Clona este repositorio:
    ```bash
    git clone https://github.com/Renehdez-97/blog-django.git
    ```

2. Accede al directorio del proyecto:
    ```bash
    cd blog-django
    ```

3. Instala las dependencias utilizando pipenv:
    ```bash
    pipenv install
    ```

4. Para ejecutar el servidor, usa:
    ```bash
    pipenv run python manage.py runserver
    ```

5. El usuario del administrador predeterminado es:
    - Usuario: `renhdz`
    - Contraseña: `12345`

   Puedes crear un nuevo superusuario con:
    ```bash
    pipenv run python manage.py createsuperuser
    ```

6. Inicia el servidor y accede a `http://127.0.0.1:8000/` en tu navegador.

