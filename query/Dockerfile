FROM node:22.15.0-alpine3.20

WORKDIR /usr/query

COPY package.json .

RUN npm i

COPY ./ ./

CMD [ "npm" ,"run","start" ]