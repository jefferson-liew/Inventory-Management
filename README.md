# Vue2 Project with Django as Backend

## Project setup
```
npm install
```

## We need to use virtualenvironment as there are python packages involved.
### 1. Download virtual environment

### 2. activate virtual environment 

### For MacOS

```
source <name of virtualenv>/bin/activate
```
### For Windows, but just check online to learn about how to activate virtual environment for windows

```
https://mothergeo-py.readthedocs.io/en/latest/development/how-to/venv-win.html
```

### 3. installing all packages by reading and installing line by line in requirements.txt

```
pip install -r requirements.txt
```

### 4. running the django server

```
python api/manage.py runserver
```

### 5. Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### In the event that you installed another python package and want to add it to the requirements.txt file, just delete the old file and type
```
pip freeze > requirements.txt
```