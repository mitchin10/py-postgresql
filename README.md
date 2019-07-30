py-postgresql

Using PostgreSQL database.

1. Access PostgreSQL to create database

sudo -u postgres psql

create datebase database_name;

grant all privileges on database_name to pg_user;

2. If require install psycopg2

pip3 install psycopg2

3. Setup database connection in setting.py => https://docs.djangoproject.com/en/2.2/ref/settings/#databases

4. Run migration

python manage.py makemigrations

python manage.py migrate

5. Create an administrative account

python manage.py createsuperuser
