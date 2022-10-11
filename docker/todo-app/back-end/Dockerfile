# COLOCAR IMAGEM BASE
FROM node:14 AS todobackend

WORKDIR /app

EXPOSE 3001

ADD ./node_modules.tar.gz .
COPY ./src .
COPY ./package-lock.json .
COPY ./package.json .

CMD ["npm", "start"]