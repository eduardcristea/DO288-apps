FROM node:latest
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY package*.json ./
RUN npm i express
# Bundle app source
COPY . .
EXPOSE 3000
CMD [ "node", "server.js"]
