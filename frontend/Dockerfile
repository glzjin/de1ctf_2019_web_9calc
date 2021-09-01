FROM node:16.8.0-alpine3.13
WORKDIR /app
COPY package.json /app/package.json
COPY yarn.lock /app/yarn.lock
RUN yarn
COPY ./ /app

CMD ["npm", "start"]
