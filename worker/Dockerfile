FROM node:12.16.1-buster

WORKDIR '/usr/app'

COPY ./package.json ./
RUN npm install

COPY . .

CMD ["npm", "run", "start"]
