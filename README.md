# recipe-app-api
Recipe API Project

docker build . // it will automatically pick Dockerfile 
docker-compose build // it will automatically pick docker-compose.yml


docker-compose run --rm app sh -c "flake8" // to run linting

docker-compose run --rm app sh -c "django-admin startproject app ." // to create the django project django-admin is installed by django dependencies i.e. django cli command

docker-compose up // to start the service

docker-compose run --rm app sh -c "python manage.py test" // test run

http://127.0.0.1:8000
