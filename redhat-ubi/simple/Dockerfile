FROM registry.access.redhat.com/ubi8/ubi

RUN dnf install -y python3

CMD mkdir /myapp

WORKDIR /myapp

COPY ./myapp.sh .

CMD ./myapp.sh
