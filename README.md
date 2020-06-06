# Todo API application

### You'll use a virtualenv to controll the packages 📦 

<li>On Linux

   ```sh
   python3 -m venv venv
   ```

</li>

<li>On Windows

   ```sh
   py -3 -m venv venv
   ```

</li>

<li>On Mac
   
   ```sh
   virtualenv venv
   ```

</li>

## After activate run this

   ```sh
   (venv)pip install -r requirements.txt
   ```

## Migrate to create the database table

   ```sh
   (venv) cd myproject
   (venv) python manage.py migrate
   ```

## Make admin user

   ```sh
   (venv) python manage.py createsuperuser
   ```

## Runserver

   ```sh
   (venv) cd myproject
   (venv) python manage.py runserver
   ```