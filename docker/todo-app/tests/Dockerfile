FROM mjgargani/puppeteer:trybe1.0 AS todotests


WORKDIR /app

COPY . .

ADD node_modules.tar.gz /app/node_modules

EXPOSE 3001
ENTRYPOINT [ "npm" ]


CMD [ "test" ]
