# Vue2 Project with Django as Backend
## • Purpose
Develop a web application that enables the quantity of stock to be updated in real time across all the different ecommerce platforms. This project will be considered complete when the quantity of stock can be updated in real time. This project supports E-Commerce vendors to ensure a smooth online shopping for consumers.

## • Contributors
- Jefferson Liew (Backend / Frontend connection to Backend)
- Richie Ang (Frontend)
- Marcus Teh (Frontend)
- Ryan (Documentation)
- Xin Kai (Documentation)
- Lyndon (Documentation

## Project setup
```
npm install
```

## Use virtual environment for python packages involved.
### 1. Download virtual environment
```
https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/
```

### 2. Activate virtual environment 

### For MacOS

```
source <name of virtualenv>/bin/activate
```
### For Windows, but just check online to learn about how to activate virtual environment for windows

```
https://mothergeo-py.readthedocs.io/en/latest/development/how-to/venv-win.html
```

### 3. Installing all packages in requirements.txt

```
pip install -r requirements.txt
```

### 4. Running the django server

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
