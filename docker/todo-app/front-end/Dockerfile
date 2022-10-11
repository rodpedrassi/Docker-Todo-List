FROM node:14-alpine AS todofrontend

WORKDIR /app

EXPOSE 3000

ADD node_modules.tar.gz .
COPY ./src ./src
COPY ./public ./public
COPY package-lock.json .
COPY package.json .

CMD ["npm", "start"]