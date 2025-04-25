FROM python:3.13.3-alpine3.21

COPY ./requirements.txt .

RUN pip install -r /requirements.txt

COPY ../src /src

CMD python /src/app.py
