FROM node:alpine

WORKDIR /usr/src/app
RUN npm install && npm install pm2 -g
CMD pm2 --name budgetish start npm -- start && /bin/sh