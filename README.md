docker-compose up --build
docker-compose run django python manage.py migrate
docker-compose run django python manage.py createsuperuser
