# BEFORE

sudo apt-get install postgresql



# Example todoapp project

heroku create 
git push heroku master
heroku run python manage.py migrate
heroku run python manage.py createsuperuser

#Чтобы добавить memcached в проект, подключите его как addon:

heroku addons:create memcachier:dev