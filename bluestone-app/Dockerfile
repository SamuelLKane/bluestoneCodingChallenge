FROM node:13.10.1-alpine
WORKDIR /tmp/bluestone-app
COPY package.json .
RUN npm install --quiet
COPY . .