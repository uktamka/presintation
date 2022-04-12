FROM node:15.12.0 AS builder
WORKDIR /app

COPY package*.json /app/

RUN npm install

COPY . /app
RUN npm run build

