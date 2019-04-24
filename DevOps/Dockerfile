FROM node:alpine

WORKDIR /home/node

RUN mkdir devops-303

COPY devops-303/ ./devops-303/

WORKDIR /home/node/devops-303

RUN npm install

EXPOSE 8884

CMD node app.js
