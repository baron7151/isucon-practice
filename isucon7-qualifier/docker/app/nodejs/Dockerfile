FROM node:6.11

ARG GIT_URL=https://github.com/baron7151/isucon7-practice.git

RUN git clone $GIT_URL /home/isucon/isubata
WORKDIR /home/isucon/isubata/webapp/nodejs
RUN npm install

EXPOSE 5000

ENTRYPOINT ["node", "/home/isucon/isubata/webapp/nodejs"]
