FROM node:20

WORKDIR /usr/app

COPY . .

RUN npm i

RUN npm run build

CMD ["npm", "run", "start:prod"]
