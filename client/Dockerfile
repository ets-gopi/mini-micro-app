FROM node:22.15.0-alpine3.20

ENV CI=true

ENV WDS_SOCKET_PORT=0

WORKDIR /usr/client

COPY package.json .

RUN npm i

COPY ./ ./

CMD [ "npm" ,"run","start" ]