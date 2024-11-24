FROM python:3.10-alpine3.20

WORKDIR /app

COPY . /app

RUN pip install -r requierments.txt

EXPOSE 4999

ENV PORT="4999"

CMD ["python3","main.py"]