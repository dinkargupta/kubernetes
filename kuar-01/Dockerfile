# start from a Node.JS 10 (LTS) image
FROM node:10

# specify the directory inside the image in which all commands will run
WORKDIR /usr/src/app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

#copy all of the app files into the image
COPY . .

# The default command to run when startting the container
CMD ["npm", "start"]