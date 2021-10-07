# Dockerfile for React cliet

# Build react client
FROM node:16.10-alpine

# Working directory
WORKDIR /usr/src/app

COPY package*.json ./

### Install dependencies

RUN npm install --silent

# copy local files to app folder

COPY . .

EXPOSE 3000

CMD ["npm", "start"]