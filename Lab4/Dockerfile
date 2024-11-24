FROM python:3.10-alpine3.20

ENV FLASK_APP=color.py
ENV APP_COLOR="green"

WORKDIR /app

COPY . /app

RUN pip install -r requierments.txt

EXPOSE 8080

CMD ["python","color.py"]