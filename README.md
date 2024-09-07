# [Livraria Online]

<br/>

## Quick start

> Descompacte ou clone o repositório privado. Após obter o código, abra um terminal e navegue até o diretório de trabalho, com o código-fonte do produto.

<br />

```bash
$ # Get the code
$ git clone https://github.com/creativetimofficial/argon-dashboard-django.git
$ cd argon-dashboard-django
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv venv
$ source venv/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv venv
$ # .\venv\Scripts\activate
$
$ # Install modules - SQLite Storage
$ pip3 install -r requirements.txt
$
$ # Crie as tabelas
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port
$ # python manage.py runserver 0.0.0.0:<your_port>
$
$ # Access the web app in browser: http://127.0.0.1:8000/
```

> Note: To use the app, please access the registration page and create a new user. After authentication, the app will unlock the private pages.


<br />

## Recompile CSS

# teste
# teste
