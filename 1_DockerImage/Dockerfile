FROM python:3.8.10

WORKDIR /app

COPY . /app

RUN pip install flask

EXPOSE 5000

CMD ["flask", "--app", "test", "run", "--host=0.0.0.0"]
