FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

# Install
RUN npm ci

COPY . .

EXPOSE 8080

CMD [ "npm", "run", "prod" ]