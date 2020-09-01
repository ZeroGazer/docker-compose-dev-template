FROM python:3.8.5-alpine3.12

WORKDIR /temp

COPY ./requirements.txt .

RUN pip install -r ./requirements.txt

WORKDIR /usr/src/app

ENTRYPOINT ["python", "main.py"]
