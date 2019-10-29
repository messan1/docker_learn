FROM node:carbone-alpine

WORKDIR /infinity

COPY package.*json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node","app.js" ]