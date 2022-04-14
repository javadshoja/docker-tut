FROM node:lts-alpine

WORKDIR /usr/app

RUN npm i -g pnpm

COPY package.json .

RUN pnpm i

COPY . .

CMD ["pnpm","dev"]
