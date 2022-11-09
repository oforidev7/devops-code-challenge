FROM node:16.10.0

WORKDIR /app

COPY . /app

RUN yarn install

RUN yarn build

CMD yarn start

EXPOSE 3000