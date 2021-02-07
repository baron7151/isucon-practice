FROM golang:1.9

ARG GIT_URL=https://github.com/baron7151/isucon7-practice.git

RUN git clone $GIT_URL /home/isucon/isubata
WORKDIR /home/isucon/isubata/webapp/go
RUN make

EXPOSE 5000

ENTRYPOINT ["/home/isucon/isubata/webapp/go/isubata"]
