FROM alpine:latest

RUN apk add --update nodejs nodejs-npm

RUN apk add --update bash

RUN npm install -g react-native-cli

RUN apk update

WORKDIR /var/www

EXPOSE 3000

CMD tail -f /dev/null

# Start a new project
# react-native init <project_name>