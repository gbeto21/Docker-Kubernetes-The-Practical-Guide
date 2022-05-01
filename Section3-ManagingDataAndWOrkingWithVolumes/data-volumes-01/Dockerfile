FROM node:14

WORKDIR /app

##Copy package.json to the working directory
##Already specified previously
COPY package.json .

RUN npm install

COPY . .

ARG DEFAULT_PORT=80

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

##Path inside of the container
##VOLUME ["/app/feedback"]

CMD ["npm", "start"]
