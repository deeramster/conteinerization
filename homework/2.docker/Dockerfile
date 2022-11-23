FROM python:2.7-alpine

WORKDIR /opt/demo/
COPY /python .

RUN pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT python app.py
