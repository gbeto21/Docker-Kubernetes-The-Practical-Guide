FROM node:14

WORKDIR /app

##Copy package.json to the working directory
##Already specified previously
COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "server.js"]
