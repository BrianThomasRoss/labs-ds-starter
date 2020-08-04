# pull official base image
FROM python:3.7-slim-buster

# set working directory
WORKDIR /usr/src/app

# install python dependencies
COPY ./requirements.txt .
RUN pip install --upgrade pip \
    && pip install -r requirements.txt

# add app
COPY . .
