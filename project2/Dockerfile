FROM debian

RUN apt-get update -y

RUN apt-get install curl -y 

RUN curl -fsSL https://code-server.dev/install.sh | sh

CMD ["code-server", "--bind-addr=0.0.0.0:8080"]

