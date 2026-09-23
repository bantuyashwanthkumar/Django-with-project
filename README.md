step - 1
Create a Box
python -m venv venv

Step - 2
inside a box open terminal and type to activate the venv
.\venv\Scripts\Activate.ps1

Step - 3
Install Django
pip install django

step - 4
verify installation
python -m django --version 

-----------------------------------------------
start project - 5
python -m django startproject myproject .
-----------------------------------------------

step - 5.5
make an app in the project
python manage.py startapp <appname>

--------------------------------------------

step - 6
to run django === python manage.py runserver


-------------------------------------------
===== migration === 
#first register ur apps in the settings.py

python manage.py makemigrations
python manage.py migrate

-------------------------------------------
