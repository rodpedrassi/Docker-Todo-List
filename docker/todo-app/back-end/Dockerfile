FROM node:14-alpine AS todobackend

WORKDIR /app

EXPOSE 3001

ADD node_modules.tar.gz .
COPY ./src ./src
COPY package-lock.json .
COPY package.json .

CMD ["npm", "start"]