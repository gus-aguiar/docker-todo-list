FROM node:14 AS todobackend


WORKDIR /app

COPY . .

ADD node_modules.tar.gz /app/node_modules

EXPOSE 3001
ENTRYPOINT [ "npm" ]


CMD [ "start" ]