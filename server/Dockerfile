FROM node:alpine

WORKDIR /usr/src/app
COPY ./budgetish_react/ ./
RUN npm install --quiet
COPY ./budgetish_react/ .
RUN npm run start