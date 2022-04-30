FROM node

#Place where the commands will be executed
WORKDIR /app

COPY package.json /app

RUN npm install

#Host file syste  |  Image/ container file system
COPY . /app

#Copy al the files to the Working directory (/app)
# COPY . ./

EXPOSE 80

#Comands are executed when the container is started
CMD ["node","server.js"]
