# django-resume-builder
This is the base project for the SteamaCo Django resume builder assessment.

## Setup
- Install `python`, `pip`, and `virtualenv` for your platform
- Clone this repository
- Create a virtual environment in the repository's base directory. `env` has already been added to the `.gitignore`.
- Install the dependencies in `requirements.txt`
- Run `python manage.py migrate`
- *Optional*: Create a superuser using `python manage.py createsuperuser`. This account may be used to access the Django admin site at `/admin/`.

## Local server
`python manage.py runserver`

## Code style
This repository follows the [PEP8](https://www.python.org/dev/peps/pep-0008/) standard. `pep8 apps/` should produce no warnings.
