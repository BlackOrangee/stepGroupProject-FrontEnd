FROM node:18

WORKDIR /usr/src/app

COPY build .

RUN npm install -g serve

CMD ["serve", "-s", ".", "-l", "80"]
