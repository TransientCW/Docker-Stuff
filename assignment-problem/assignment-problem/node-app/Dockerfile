FROM node:latest

WORKDIR /app

COPY ./package.json .

RUN npm install

COPY ./server.js .

EXPOSE 3000/tcp

CMD ["node", "server.js"]

