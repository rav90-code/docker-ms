FROM node

WORKDIR /app

COPY package*.json ./

#Install app dependencies

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

