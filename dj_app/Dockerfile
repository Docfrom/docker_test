FROM python:latest

WORKDIR /app

COPY ./app /app

RUN pip install -r /app/requirements.txt

RUN python manage.py migrate

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000"]