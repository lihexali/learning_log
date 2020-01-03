## create env
cd learning_log

python -m venv ll_env

source ll_env/bin/activate

pip install Django pylint yapf pylint_django

python manage.py runserver

