## Django Rest Framework

This is a demo project with a simple authentication API consumed by a vuejs application. 
The other project (vuejs) can be found at: https://github.com/ppmadalin/vuejs-django-auth-frontend

# How to use install?

1. Clone the repository.
2. Create a new virtualenv `python3 -m venv .venv`
3. Switch to new virtualenv `.venv\Scripts\activate` or `source .venv/bin/activate` 
4. Install requirements `pip install -r requirements.txt`
5. Run migrations `python manage.py migrate`
6. Create a new user `python manage.py createsuperuser --email admin@example.com --username admin
`



