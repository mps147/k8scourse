FROM python:3

RUN apt-get update -y && \
    apt-get install -y python3-pip python-dev

WORKDIR /app

RUN pip install Flask
RUN pip install requests

COPY . .

EXPOSE 3001

CMD ["python", "./app.py"]