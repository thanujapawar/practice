FROM ubuntu:latest

#set the working dirrectory on thee image

WORKDIR /app


COPY . /app

RUN apt-get update && apt-get install -y python3 python3-pip

CMD ["python3" ,"app.py" ]
