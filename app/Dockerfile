FROM python:3.6-alpine3.10

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY app.py /app

EXPOSE 5000

CMD python app.py

# Docker container for nano editor.
# Version 0.1

#FROM ubuntu:14.04

#RUN apt-get update && \
#    apt-get install -y nano && \
#    rm -fr /var/lib/apt/lists/*

#CMD ["bash"]