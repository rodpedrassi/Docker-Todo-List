FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /app

ADD node_modules.tar.gz .
COPY ./e2e ./e2e
COPY package-lock.json .
COPY package.json .
COPY jest.config.js .

CMD ["npm", "test"]