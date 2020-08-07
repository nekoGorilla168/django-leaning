FROM python:3.8.5-buster AS dev
ENV PYTHONUNBUFFERED 1
WORKDIR /code
RUN apt-get update && apt-get install git
RUN pip install --upgrade pip
ADD requirements.txt /code
RUN pip install -r requirements.txt

