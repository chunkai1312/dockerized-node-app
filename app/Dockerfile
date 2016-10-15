FROM node:argon

MAINTAINER Chun-Kai Wang <chunkai1312@gmail.com>

RUN mkdir -p /app
WORKDIR /app

COPY package.json /app
RUN npm install

COPY . /app

EXPOSE 8080
CMD [ "npm", "start" ]
