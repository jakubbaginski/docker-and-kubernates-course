FROM node:alpine

WORKDIR /usr/app

# installing dependencies
COPY ./package.json ./
RUN npm install

# copying rest of the files
COPY ./ ./

# image start command
CMD ["npm", "start"]
