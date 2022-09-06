FROM node:16-alpine as builder

WORKDIR /usr/src/app

COPY package*.json yarn.lock ./

RUN yarn

COPY . .

# CMD ["node", "dist/src/main"]

EXPOSE 3000