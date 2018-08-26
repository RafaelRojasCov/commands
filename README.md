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
  
- Pip Package
  - For install fake data population scripts: `pip install Faker`
  - For install flask API framework: `pip install flask`
  - For install virtual env: `pip -m install virtualenv`
  - For install flask & Flask-REST: `pip install Flask-RESTful`
  - For Auth & Logging in Flask: `pip install Flask-JWT`
  
- For create a new env `python -m venv path/to/virtual/environment`

## ***Django***
- For start environment: `path/to/env/scripts/activate.bat`
- For stop environment:  `path/to/env/scripts/deactivate.bat`
- For create a new project: `django-admin startproject nameofproject`
- For run server in a project directory: `python manage.py runserver`
- For create a new app inside a project: `python manage.py startapp app_name`
- Create the SQL database from models: `python manage.py migrate`
- Register the changes of Models to the app: `python manage.py makemigrations nameofapp`
- Create a super user: `python manage.py createsuperuser`


## ***NodeJS***
- For install React: `npm install -g create-react-app`
- For install tachyons: `npm install --save tachyons`
- For install Redux: `npm install --save redux`
- For install the connector between React & Redux: `npm install --save react-redux`
- For install enzyme testing package: `npm install --save enzyme-adapter-react-{version}`
  - {version} means the number of the version of React project where we want to install on it.
- For install styled-components library for React: `npm install --save styled-components`
- For install font-awesome icons:
  - `npm i --save @fortawesome/fontawesome-svg-core`
  - `npm i --save @fortawesome/free-solid-svg-icons`
  - `npm i --save @fortawesome/react-fontawesome`
  - `npm i --save @fortawesome/fontawesome-free-solid`
  - `npm i --save @fortawesome/fontawesome-free-brands`
  - `npm i --save @fortawesome/fontawesome-free-regular`

