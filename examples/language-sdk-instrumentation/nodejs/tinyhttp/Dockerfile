FROM node:latest

WORKDIR /app

COPY package.json yarn.lock .
RUN yarn install

COPY index.js .

CMD ["node", "index.js"]
