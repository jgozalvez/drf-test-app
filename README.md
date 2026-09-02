# drf-test-app

Use of Linting
```docker compose run --rm app sh -c "flake8"```

Run tests
```docker compose run --rm app sh -c "python manage.py test"```

Install Django
```docker compose run --rm app sh -c "django-admin startproject app ."```