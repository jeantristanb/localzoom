FROM node:18-alpine

WORKDIR /app

RUN apk add --no-cache git

RUN git clone https://github.com/statgen/localzoom.git .

ENV NODE_OPTIONS=--openssl-legacy-provider


RUN npm install

EXPOSE 8080

#npm run serve
CMD ["npm", "run","serve"]
