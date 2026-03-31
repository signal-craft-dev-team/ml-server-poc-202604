FROM python:3.11-slim

WORKDIR /app
COPY train/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY common/ ./common/
COPY train/ ./train/

CMD ["python", "-m", "train.app.main"]