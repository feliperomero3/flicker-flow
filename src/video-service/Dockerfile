FROM node:20.12.1-slim

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm ci --omit=dev

COPY ./src ./src

CMD [ "npm", "start"]
