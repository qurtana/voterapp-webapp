FROM python:3.11-alpine3.19

ENV PYTHONBUFFERED=1

WORKDIR /app

COPY requirements.txt requirements.txt
COPY . .

RUN pip install -r requirements.txt

CMD python manage.py runserver 0.0.0.0:8000
