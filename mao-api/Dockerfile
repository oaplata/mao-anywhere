FROM node:10

WORKDIR /usr/src/mao

ADD package.json .

RUN npm install

ADD . .

CMD ["npm", "run", "start"]