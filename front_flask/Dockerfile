# Dockerfile del FRONT — Flask + Jinja2 + Bootstrap (puerto 8064)
FROM python:3.12-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
ENV PUERTO=8064
EXPOSE 8064
CMD ["python", "app.py"]
