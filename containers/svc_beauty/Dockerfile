FROM node:23-alpine

RUN mkdir /var/log/node
WORKDIR /app
RUN npm install -g nodemon

# Устанавливаем PostgreSQL клиент
RUN apk update && apk add postgresql-client

CMD npm run start:dev

