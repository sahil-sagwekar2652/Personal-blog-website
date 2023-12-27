FROM python:3.11.6-slim-bullseye

WORKDIR ~/flask_blog

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

CMD ["python3", "main.py"]
