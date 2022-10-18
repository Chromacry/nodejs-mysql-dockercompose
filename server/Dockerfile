# syntax=docker/dockerfile:1
FROM node:18.9.0
ENV NODE_ENV=development
WORKDIR /server-app

RUN npm install node
RUN npm install -g nodemon
COPY package*.json .
# COPY server.js .
COPY . .