FROM alpine:latest

RUN apk add --update nodejs nodejs-npm

RUN apk add --update bash

RUN npm install -g @vue/cli

RUN apk update

WORKDIR /var/wwww

EXPOSE 3000

EXPOSE 8000

EXPOSE 8080

CMD tail -f /dev/null

# Cria aplicação
# vue create <app_name>

# Iniciando server
# npm run serve

# Iniciando vue ui
# vue ui --headless --port 8000 --host 0.0.0.0