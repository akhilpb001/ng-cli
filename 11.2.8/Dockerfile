FROM node:14.16.1-alpine3.13

ENV NG_CLI_VERSION 11.2.8

RUN npm install -g @angular/cli@$NG_CLI_VERSION

WORKDIR /app

COPY docker-entrypoint.sh /usr/local/bin/

EXPOSE 4200

ENTRYPOINT ["docker-entrypoint.sh"]

CMD ["ng", "version"]
