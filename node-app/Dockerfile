FROM node:9-alpine
RUN apk update && apk add git
RUN npm install express
RUN mkdir node
WORKDIR /node
RUN git clone https://github.com/kkenan/basic-microservices.git
WORKDIR /node/basic-microservices/node-app
EXPOSE 8081
ENTRYPOINT ["node", "index.js"]