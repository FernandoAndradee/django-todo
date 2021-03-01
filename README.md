# Todo App

Para ver em produção [entre aqui](https://tarefas-afazer.herokuapp.com/)

### Use virtualenv para controlar os pacotes da aplicação 📦 

<li>No Linux

   ```sh
   python3 -m venv venv
   ```

</li>

<li>No Windows

   ```sh
   py -3 -m venv venv
   ```

</li>

<li>No Mac
   
   ```sh
   virtualenv venv
   ```

</li>

## Instale as dependências 

   ```sh
   (venv)pip install -r requirements.txt
   ```

## Migre para criar as tabelas do banco de dados

   ```sh
   (venv) cd myproject
   (venv) python manage.py migrate
   ```

## Crie um admin user

   ```sh
   (venv) python manage.py createsuperuser
   ```

## Rode o servidor

   ```sh
   (venv) cd myproject
   (venv) python manage.py runserver
   ```
