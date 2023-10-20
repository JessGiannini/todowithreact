FROM node:16-slim
MAINTAINER label="Rohan Rustagi"
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --only=production
COPY . .
EXPOSE 3000
CMD ["npm", "start"]

