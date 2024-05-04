# To Start Server use: python3 manage.py runserver

## Below Commands are for Env Set Up and Project Set Up
```
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % ls
README.md
```

```
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % pip3 -V
pip 24.0 from /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/pip (python 3.12)
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % python3 -m pip --version
pip 24.0 from /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/pip (python 3.12)
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % pip3 --version          
pip 24.0 from /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/pip (python 3.12)
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % python3 -m django --version
5.0.3
```

```
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % pip3 install django
Requirement already satisfied: django in /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages (5.0.3)
Requirement already satisfied: asgiref<4,>=3.7.0 in /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages (from django) (3.8.1)
Requirement already satisfied: sqlparse>=0.3.1 in /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages (from django) (0.4.4)
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % mkdir dl_crm
sajeedsaif@Sajeeds-MacBook-Air DjangoCRM % cd dl_crm
sajeedsaif@Sajeeds-MacBook-Air dl_crm % python3 -m venv env
sajeedsaif@Sajeeds-MacBook-Air dl_crm % source env/bin/activate
(env) sajeedsaif@Sajeeds-MacBook-Air dl_crm % pip3 install Django
Collecting Django
  Using cached Django-5.0.4-py3-none-any.whl.metadata (4.1 kB)
Collecting asgiref<4,>=3.7.0 (from Django)
  Using cached asgiref-3.8.1-py3-none-any.whl.metadata (9.3 kB)
Collecting sqlparse>=0.3.1 (from Django)
  Using cached sqlparse-0.5.0-py3-none-any.whl.metadata (3.9 kB)
Using cached Django-5.0.4-py3-none-any.whl (8.2 MB)
Using cached asgiref-3.8.1-py3-none-any.whl (23 kB)
Using cached sqlparse-0.5.0-py3-none-any.whl (43 kB)
Installing collected packages: sqlparse, asgiref, Django
Successfully installed Django-5.0.4 asgiref-3.8.1 sqlparse-0.5.0
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air dl_crm % python3 -m django --version
5.0.4
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air dl_crm % django-admin startproject digital_lync_crm
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air dl_crm % ls
digital_lync_crm        env
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air dl_crm % cd digital_lync_crm
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % ls
digital_lync_crm        manage.py
```

```
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % python3 manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
May 02, 2024 - 08:44:14
Django version 5.0.4, using settings 'digital_lync_crm.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.

[02/May/2024 08:44:17] "GET / HTTP/1.1" 200 10629
Not Found: /favicon.ico
[02/May/2024 08:44:17] "GET /favicon.ico HTTP/1.1" 404 2120
^C%
```
```                                                                                                                                                                    
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % ls
db.sqlite3              digital_lync_crm        manage.py
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % python3 manage.py startapp leadmodule
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % ls
db.sqlite3              digital_lync_crm        leadmodule              manage.py
(env) sajeedsaif@Sajeeds-MacBook-Air digital_lync_crm % cd leadmodule
(env) sajeedsaif@Sajeeds-MacBook-Air leadmodule % ls
__init__.py     admin.py        apps.py         migrations      models.py       tests.py        views.py
(env) sajeedsaif@Sajeeds-MacBook-Air leadmodule %
```
