FROM node:12.13.1-alpine3.10

ENV EMBER_CLI_VERSION 3.20.0

RUN npm install -g ember-cli@$EMBER_CLI_VERSION

WORKDIR /app

EXPOSE 4200

CMD ["ember", "version"]
