FROM node:14.16.1-alpine3.13

ENV EMBER_CLI_VERSION 3.24.0

RUN npm install -g ember-cli@$EMBER_CLI_VERSION

WORKDIR /app

EXPOSE 4200

CMD ["ember", "version"]
