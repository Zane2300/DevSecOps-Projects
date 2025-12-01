# ❌ Use deprecated image

#FROM python:3.6
FROM python:3.11-alpine

WORKDIR /app

RUN pip install flask

COPY app.py .

CMD [ "python", "app.py" ]