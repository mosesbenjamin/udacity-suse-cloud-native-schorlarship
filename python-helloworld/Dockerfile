FROM python:3.9.5
LABEL maintainer="Moses Benjamin"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

CMD ["python", "app.py"]