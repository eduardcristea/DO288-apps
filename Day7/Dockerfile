FROM node:latest
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY package*.json ./
COPY test.sql ./
RUN npm install express
RUN npm install mysql 
# Bundle app source
COPY . .
EXPOSE 3000
CMD [ "node", "server.js"]
