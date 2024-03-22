## base image node
FROM node:21-alpine

## installing create react app globally in the container 


RUN mkdir -p /usr/src/app
# set working directory
WORKDIR /usr/src/app


#install node dependencies
COPY . .
RUN npm install --silent
RUN npm install react-scripts@5.0.1 -g --silent


