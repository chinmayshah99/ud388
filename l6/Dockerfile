FROM python:3.6.7-alpine3.6

LABEL maintainer="Chinmay Shah <chinmayshah3899@gmail.com>"

COPY requirements.txt /app/
WORKDIR /app
RUN pip install -r requirements.txt

COPY . /app
WORKDIR /app

ENTRYPOINT ["python"]

CMD ["views.py"]

# CMD ["endpoint_test.py"]
