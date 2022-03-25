FROM node:16.14.2-alpine3.15

ENV NG_CLI_VERSION 13.3.0

RUN npm install -g @angular/cli

RUN apk add git

WORKDIR /app

EXPOSE 4200

CMD ["ng", "version"]
