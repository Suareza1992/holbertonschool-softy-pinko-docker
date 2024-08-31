FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y

FROM python:latest

RUN pip3 install flask

COPY . /app

WORKDIR /app

EXPOSE 5252

CMD ["python3", "api.py"]
