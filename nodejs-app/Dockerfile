FROM node:18-alpine

WORKDIR /nodejs-app/

COPY package*.json ./

RUN npm install express

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
