FROM node:13-alpine

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn install
COPY . /app
RUN yarn build
