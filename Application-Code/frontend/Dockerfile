FROM node:18

WORKDIR /usr/src/app
COPY . .

RUN npm install
ENV NODE_OPTIONS=--openssl-legacy-provider
CMD ["npm", "start"]
