FROM node:7
WORKDIR /app
COPY package.json .
COPY *.JS .
RUN npm install
EXPOSE 8080
CMD [ "node", "server.js" ]