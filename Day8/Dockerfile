FROM node:latest
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY . .
RUN npm install express && npm install mysql 
# Bundle app source
EXPOSE 3000
CMD [ "node", "server.js"]
