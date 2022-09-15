# pull official base image
FROM node:16-alpine3.15

COPY . .

RUN npm i

RUN npm run build

EXPOSE 80

CMD node ./dist/main.js

