FROM node:14 AS todofrontend


WORKDIR /app

COPY . .

ADD node_modules.tar.gz /app/node_modules

EXPOSE 3000
ENTRYPOINT [ "npm" ]


CMD [ "start" ]
