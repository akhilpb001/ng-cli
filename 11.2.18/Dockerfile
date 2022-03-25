FROM node:14.16.1-alpine3.13

ENV NG_CLI_VERSION 11.2.18

RUN npm install -g @angular/cli@$NG_CLI_VERSION

RUN apk add git

WORKDIR /app

EXPOSE 4200

CMD ["ng", "version"]
