FROM python:3.8-slim
WORKDIR /App
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
ENV NAME World
CMD ["python", "App.py"]
