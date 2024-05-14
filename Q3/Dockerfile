
FROM python:3.9-slim-buster

WORKDIR /app

ADD . /app

RUN python

EXPOSE 80

ENV NAME World

CMD ["python", "app.py"]