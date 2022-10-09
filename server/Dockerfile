# syntax=docker/dockerfile:1
FROM node:18.9.0
ENV NODE_ENV=development

WORKDIR /server-app
COPY package*.json .
COPY server.js .

CMD npm start
