#syntax=docker/dockerfile:1

FROM python:3.8-slim-buster

WORKDIR /python-docker

COPY code/requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY code/. .

CMD ["python", "app.py"]