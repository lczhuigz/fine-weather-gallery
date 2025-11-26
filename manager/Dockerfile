FROM python:3.11-alpine

COPY requirements.txt .

RUN apk add --no-cache build-base libffi-dev zlib-dev jpeg-dev
RUN pip install --no-cache-dir gunicorn
RUN pip install --no-cache-dir -r requirements.txt
