FROM node:12.22.1-alpine3.12

ENV NG_CLI_VERSION 9.1.15

RUN npm install -g @angular/cli@$NG_CLI_VERSION

WORKDIR /app

EXPOSE 4200

CMD ["ng", "version"]
