FROM node:17.7-alpine
WORKDIR /react
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
RUN npm run build