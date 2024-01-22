FROM python:3.8-slim-buster

RUN pip install "arkitekt[cli]>=0.7.0a6"

# Add in a lot of ROCm dependencies

RUN mkdir /app
WORKDIR /app
COPY .arkitekt /app/.arkitekt
COPY app.py /app/app.py
