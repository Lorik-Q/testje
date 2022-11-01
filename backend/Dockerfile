FROM node:17-alpine3.14

WORKDIR /node/app

COPY *.js /node/app

COPY *.json /node/app

RUN npm install

CMD ["node", "index.js"]

EXPOSE 3000
