# Commands
List of usefull shorthands found in the Internet

## ***Windows***

#### ***Windows version***
- In command prompt or powershell:

``` 
wmic os get caption
wmic os get osarchitecture
doskey nameofmacro="path/to/executable.bat"
doskey nameofalias="nameofcommand"
```

## ***Python***

- MySQL
  - For install MySQL Database Connector: `pip install mysql-python`
  - For use it in Python program: `import MySQLdb`
  
- Django
  - For start environment: `path/to/env/scripts/activate.bat`
  - For stop environment:  `path/to/env/scripts/deactivate.bat`
  - For run server in a project directory: `python manage.py runserver` //it will run at localhost:8000
  - For create a new app inside a project: `python manage.py startapp app_name` //it will create a new app
