# atio-python-djanggo

Belajar python menggunakan framework djanggo

1. create virtual environment

   ```sh
   $ python -m venv venvname
   ```

2. Activate and deactivate virtual environment

   - On Windows
     activate venv
     ```sh
     $ venvname\Script\activate
     ```
     deactivate venv
     ```sh
     $ venvname\Script\deactivate
     ```

3. Install python packages

   ```sh
     $ pip install -r requirements.txt
   ```

4. Rename file .env.example to .env
   config database :

   > DB_DATABASE=atiodb
   > DB_USERNAME=
   > DB_PASSWORD=
   > DB_HOST=127.0.0.1
   > DB_PORT=5432

5. Run project
   ```sh
     $ python manage.py runserver
   ```
   or with port
   ```sh
     $ python manage.py runserver 8080
   ```

### Cerate new app

```sh
     $ python manage.py startapp appname
```

## License

MIT
