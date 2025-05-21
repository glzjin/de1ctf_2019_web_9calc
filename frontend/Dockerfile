FROM node:23.11.1-alpine3.21
WORKDIR /app
COPY package.json /app/package.json
COPY yarn.lock /app/yarn.lock
RUN yarn
COPY ./ /app

CMD ["npm", "start"]
