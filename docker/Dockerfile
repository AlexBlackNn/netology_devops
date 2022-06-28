FROM continuumio/miniconda3:latest
RUN mkdir -p /app
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
RUN chmod +x 1.sh
ENTRYPOINT /app/1.sh; /bin/bash
