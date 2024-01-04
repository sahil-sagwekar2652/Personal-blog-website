FROM python:3.11.6-slim-bullseye

WORKDIR ~/flask_blog

COPY . .
RUN pip3 install -r requirements.txt
RUN apt-get update && apt-get install -y curl

CMD ["gunicorn", "--bind", "0.0.0.0:5000", "wsgi:app"]
