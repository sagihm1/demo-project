FROM python:3.9-slim-buster

ADD app.py .

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

CMD ["python", "./app.py"]
