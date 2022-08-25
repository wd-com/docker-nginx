FROM node:12.22.9

WORKDIR /app

RUN npm install -g contentful-cli

COPY package.json .
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "run", "start:dev"]
