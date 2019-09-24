# Django-Dockerized-Template

Add Travis-CI build link here

## Setup

Step 1: In root directory of this project, run `docker build .`

Step 2: In same directory, run `docker-compose build`

## Django Commands

Once docker and docker-compose are setup, all other django commands can be run as follows:

```
docker-compose run app sh -c "python manage.py test"
docker-compose run app sh -c "python manage.py makemigrations"
docker-compose run app sh -c "python manage.py migrate"
docker-compose run app sh -c "python manage.py startapp myapp"
docker-compose run app sh -c "python manage.py createsuperuser"
```

etc.
