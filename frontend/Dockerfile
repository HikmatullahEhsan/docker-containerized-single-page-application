FROM node:18

WORKDIR /usr/src/app

COPY package*.json ./

# Use npm ci for faster and more reliable builds

COPY . .

EXPOSE 3000

ENV NODE_NO_WARNINGS=1
CMD ["npm", "start"]
