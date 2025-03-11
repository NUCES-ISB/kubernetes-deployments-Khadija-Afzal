FROM python:3.8-slim

WORKDIR /app
COPY app/app.py .

COPY app/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD ["python", "app/app.py"]