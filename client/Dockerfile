# Dockerfile for React client

# Build react client
FROM node:10.16-alpine

# Create app directory
WORKDIR /usr/src/app

COPY package*.json ./

###  Installing dependencies

RUN npm install --silent

# copy local files to app folder
COPY . .

EXPOSE 3001

CMD ["npm","start"]