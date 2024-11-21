FROM node:18

WORKDIR /usr/src/app

COPY package*.json ./


COPY . .

EXPOSE 3000

ENV NODE_NO_WARNINGS=1
CMD ["npm", "start"]
