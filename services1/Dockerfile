FROM python:3.10.12

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

ENV NAME services1

CMD ["python","app.py"]
