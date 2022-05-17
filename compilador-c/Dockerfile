FROM ubuntu

RUN apt -y update

RUN apt -y install build-essential

COPY . .

RUN gcc teste.c -o teste

ENTRYPOINT ["./teste"]