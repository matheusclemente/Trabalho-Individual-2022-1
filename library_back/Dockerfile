FROM python:3.9.13-buster

WORKDIR /backend

COPY requirements.txt ./
RUN pip install -r requirements.txt

COPY . .
