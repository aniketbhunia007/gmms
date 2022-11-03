web: gunicorn Gymnasium.wsgi:application --log-file - 
heroku ps:scale web=1
python manage.py migrate