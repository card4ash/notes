Title: Django Python Getting Started Cheet Sheet
Published: 11/25/2019
Tags:
    - Ubuntu
    - UbuntuTime
    - Introduction
---

Python Django GS
=================================
Installing virtualenv and virtualenvwrapper
**********************************************

Configure virtualenvwrapper and django (Windows)
**************************************************
```shell
    pip install virtualenvwrapper-win
	mkvirtualenv test
	workon test
	pip install django
	django-admin --version
	django-admin startproject hellodj
```

Install the virtualenv package
********************************

```shell
	python -m pip install --user virtualenv
```

Checking Installation 
**************************

```shell
	python -m virtualenv --version
```

Activating and Shutting down an enviroment
********************************************

```shell
	workon test
	deactivate
```


Quick Start Guide(recommended)
**********************************

```shell
    mkdir hellodj   
    cd hellodj
    python -m venv env
    .\env\Scripts\activate
    mkdir src
    pip install django
	pip freeze
    cd src
    django-admin --version
    django-admin --help
```

Clear screen in shell
************************

```shell
    import os
    cls = lambda: os.system('cls')

    >>> cls()
```
Django Python Shell
*********************

where manage.py located cd into this location. Go to python shell with below command 
```shell
    python manage.py shell
```


