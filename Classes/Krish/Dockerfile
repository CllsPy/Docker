FROM python:3.11-slim

WORKDIR /app

COPY . .

RUN pip install -r pkg.txt
CMD ["python", "app.py"]
