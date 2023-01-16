# django-vue

Um exemple de backend Django com frontend Vue

# Como usar o Github

Este é um exemplo de como montar, documentar e organizar um projeto no Github.
Neste exemplo, vemos como instalar o Django e o VueJS, e como subir o código corretamente.

## Este projeto foi feito com:

* [Python 3.8.16](https://python.org/)
* [Django 4.1.5](https://www.djangoproject.com/)
* [VueJS](https://vuejs.org/)

## Como rodar o projeto?

* Clone esse repositório.
* Crie uma virtualenv com Python 3.
* Ative a virtualenv.
* Instale as migrações.

```
git clone git@github.com:Jovennan/django-vue.git
cd django-vue
python -m venv .venv
source .venv/bin/activate
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser --username="admin" --email=""
python manage.py runserver
```

### Como rodar o frontend?

```
cd frontend
npm install
npm run server
```
