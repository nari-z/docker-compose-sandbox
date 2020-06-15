FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl openssh-client

COPY . .

CMD ["./start.sh"]