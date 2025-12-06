# salam
FROM ubuntu:latest

# salam
RUN apt-get update

# salam
RUN apt-get upgrade -y

# salam
RUN apt-get install -y python3 python3-pip

# salam
RUN pip3 install flask

# salam
WORKDIR /app

# salam
COPY . /app

# salam
EXPOSE 5252

# salam
CMD ["python3", "api.py"]
