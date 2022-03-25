FROM node:14.16.1-alpine3.13

ENV NG_CLI_VERSION 12.2.16

RUN npm install -g @angular/cli@$NG_CLI_VERSION

WORKDIR /app

EXPOSE 4200

CMD ["ng", "version"]
