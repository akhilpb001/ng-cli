FROM node:18.20.4-alpine3.20

ENV NG_CLI_VERSION 17.3.8

RUN npm install -g @angular/cli@$NG_CLI_VERSION

RUN apk add git

WORKDIR /app

EXPOSE 4200

CMD ["ng", "version"]
