# fenix

alembic
fastapi[all]
fastapi-users[sqlalchemy]
psycopg2
python-dotenv
sqlalchemy


uvicorn main:app --reload...

alembic init migrations
alembic revision --autogenerate -m "Database create"
alembic upgrade 6686afc943af
