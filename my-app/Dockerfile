FROM node:18

WORKDIR /usr/src/app

COPY dist .

RUN npm install -g serve

CMD ["serve", "-s", ".", "-l", "80"]
