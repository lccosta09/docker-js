FROM alpine:latest

RUN apk add --update nodejs nodejs-npm

RUN apk add --update bash

RUN npm install -g create-react-app

RUN apk update

WORKDIR /var/www

EXPOSE 3000

CMD tail -f /dev/null