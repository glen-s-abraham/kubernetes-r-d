FROM ubuntu

RUN apt-get update
RUN apt-get install -y python3

COPY . /opt/source-code

ENTRYPOINT FLASK_APP = /opt/source-code/app.py flask run