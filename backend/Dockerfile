FROM node:18

WORKDIR /usr/src/app

COPY package*.json ./

# Use npm ci for faster and more reliable builds
# RUN npm ci --production

COPY . .

EXPOSE 80

ENV NODE_NO_WARNINGS=1
CMD ["node", "app.js"]
