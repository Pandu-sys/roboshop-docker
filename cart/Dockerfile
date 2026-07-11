FROM node:20
COPY package.json .
COPY *.js .
WORKDIR /app
RUN npm install
EXPOSE 8080
CMD [ "node", "server.js" ]

