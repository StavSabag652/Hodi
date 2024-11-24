FROM python:3.11-alpine3.20

ENV FLASK_SERVER_PORT=9090

WORKDIR /app

COPY requirements.txt .

RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 9090

CMD [ "python3", "server.py" ]