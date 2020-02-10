# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
# COPY ./ ./
# RUN npm install

COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default Command
CMD [ "npm" ,"start"]