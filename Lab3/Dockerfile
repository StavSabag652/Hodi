FROM python:3.10-alpine3.20

ENV FLASK_APP=main.py

WORKDIR /app

COPY . /app

RUN pip install -r requierments.txt

EXPOSE 5010

CMD ["python","main.py"]