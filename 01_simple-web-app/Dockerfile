# Specify a base image
FROM node:14-alpine

# set the working directory
WORKDIR /usr/app


# install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]