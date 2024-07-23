# recipe-app-api
Recipe API project.

Test code:
docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py test && flake8"


Run docker:
docker-compose build

Run server:
docker-compose up


Swagger:
http://localhost:8000/api/docs