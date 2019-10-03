FROM node:12

WORKDIR /usr/src/app
#avoid re-caching each build
COPY package*.json ./
RUN npm install
COPY . .

CMD [ "node", "src/index.js" ]