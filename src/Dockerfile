FROM node:20.11.1-alpine
WORKDIR /app
COPY package*.json .
RUN npm install 
COPY . . 
ENTRYPOINT [ "node", "server.js" ]
EXPOSE 8080
