FROM node:alpine

WORKDIR /application
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]