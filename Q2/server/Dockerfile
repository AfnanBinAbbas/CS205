
FROM python:3.9-slim-buster

WORKDIR /app

ADD . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 80

ENV NAME World

CMD ["python", "app.py"]