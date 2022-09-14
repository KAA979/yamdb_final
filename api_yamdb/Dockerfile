FROM python:3.7-slim

WORKDIR /app

COPY /api_yamdb/requirements.txt /app

RUN pip3 install -r /app/requirements.txt --no-cache-dir

COPY ./ .

CMD python manage.py runserver 0:5000