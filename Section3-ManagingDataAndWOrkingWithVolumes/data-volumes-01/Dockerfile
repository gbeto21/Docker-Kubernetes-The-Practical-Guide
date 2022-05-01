FROM node:14

WORKDIR /app

##Copy package.json to the working directory
##Already specified previously
COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

##Path inside of the container
VOLUME ["/app/feedback"]

CMD ["node", "server.js"]
