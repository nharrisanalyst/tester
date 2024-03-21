## base image python

FROM python:3.12.1-slim-bookworm

# set working directory
WORKDIR /usr/src/app

# install python dependencies
RUN pip install --upgrade pip
COPY ./requirements.txt .
RUN pip install -r requirements.txt

COPY . .

