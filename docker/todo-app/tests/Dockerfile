FROM mjgargani/puppeteer:trybe1.0


WORKDIR /app

COPY . .

ADD node_modules.tar.gz /app/node_modules

EXPOSE 3001
ENTRYPOINT [ "npm" ]


CMD [ "test" ]
