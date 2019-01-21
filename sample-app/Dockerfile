FROM node:10.11.0-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install

COPY index.js ./

EXPOSE 3000

CMD [ "node", "index.js" ]
