# Django-Examples
Algunos ejercicios de Python con uso de Django.

# Primeros pasos para la creación del entorno
python -m pip install --upgrade pip

python -m venv djangoenv

cd djangoenv

.\Scripts\activate.bat

Verificar que está Django instalado

python -m django --version

Creamos un proyecto

django-admin startproject mysite

cd mysite

Ejecutamos el servidor

python manage.py runserver (puede que se solicite una migración)

python manage.py migrate

# Segunda parte
