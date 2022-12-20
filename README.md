Rest-API-with-Python

Run Dockerfile locally:
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" rest-api-python-flask sh -c "flask run --host 0.0.0.0"
