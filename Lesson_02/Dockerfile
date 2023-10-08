FROM python:3.9

COPY requirements.txt /app/requirements.txt

RUN pip install -r /app/requirements.txt

COPY app.py /app/app.py

EXPOSE 8080

ENTRYPOINT python /app/app.py