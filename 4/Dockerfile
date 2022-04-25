# using existing
FROM node:alpine

# working container dir
WORKDIR /usr/app

# dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# what to do
CMD [ "npm", "start" ]