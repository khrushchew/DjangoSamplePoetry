# DjangoSamplePoetry

This is a basic Django template for running your project using Poetry.

## First Step
Clone the repository using the following command:
```bash
git clone https://github.com/khrushchew/DjangoSamplePoetry.git
```

## Second Step
Check your Poetry installation by running:
```bash
poetry --version
```

## Third Step
Install all dependencies using Poetry:
```bash
poetry install
```

## Fourth Step
Run the server and enjoy:
```bash
poetry run python manage.py runserver
```

Now your project is ready to go!

## Dependencies

This project relies on the following dependencies:

- **Django**: `>=5.1.6,<6.0.0`
- **Django REST Framework**: `>=3.15.2,<4.0.0`
- **Psycopg2**: `>=2.9.10,<3.0.0` (PostgreSQL adapter for Django)
- **DRF-YASG**: `>=1.21.8,<2.0.0` (Yet Another Swagger Generator for Django REST Framework)
- **Ruff**: `>=0.9.6,<0.10.0` (A fast Python linter)
- **Pytest**: `>=8.3.4,<9.0.0` (Testing framework for Python)
