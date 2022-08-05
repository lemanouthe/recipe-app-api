# recipe-app-api
Recipe api project

## commande docker
docker build .
docker-compose build

# execute flake8
docker-compose run --rm app sh -c "flake8"
# crée le projet django
docker-compose run --rm app sh -c "django-admin startproject app ."

# lance les test de django
docker-compose run --rm app sh -c "python manage.py test"

# démarrer les services docker
docker-compose up

## User information
test@example.com
test
