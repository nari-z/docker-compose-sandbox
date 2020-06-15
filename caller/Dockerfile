FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl openssh-client

COPY . .
RUN chmod +x ./start.sh

CMD ["./start.sh"]