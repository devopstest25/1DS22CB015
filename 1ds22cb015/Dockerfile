FROM python:3.9-slim

WORKDIR /app


COPY test.py /app

RUN pip install flask

EXPOSE 5000

CMD ["python", "app.py"]
