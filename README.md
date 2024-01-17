# recipe-app-api
Recipe API project

Linting
- Install flake8 package
- Run it through Docker Compose
    docker-compose run --rm app sh -c "flake8"

Testing
- Django test suite
- Setup tests per Django app
- Run tests through Docker Compose
    docker-compose run --rm app sh -c "python manage.py test"

Creating Django project through docker
docker-compose run --rm app sh -c "django-admin startproject app ."