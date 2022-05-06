After installing the project 

Step 1
First you have to activate your virtual environment
"python3 -m venv .venv"

Step 2
You have to install the packages involved in running the project
"pip install -r requirements.txt"

Step 3
You will run python make migrations.
"python manage.py makemigrations"

Step 4
We have to migrate all the data into database by migrating
python manage.py migrate

Step 5
You run the code
"    python3 manage.py runserver"
