FROM node:18-alpine

WORKDIR /react-docker-example/

EXPOSE 5173

COPY public/ /react-docker-example/public
COPY src/ /react-docker-example/src
COPY package.json /react-docker-example/

RUN npm install
CMD ["npm", "run", "dev"]