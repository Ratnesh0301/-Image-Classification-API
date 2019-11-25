FROM python:3
WORKDIR C:\Users\Dell\Desktop\REST_API\Image Classification\web
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD ["python","app.py"]