FROM node:14

EXPOSE 3000

COPY . .

WORKDIR /frontend

ADD node_modules.tar.gz .

ENTRYPOINT ["npm", "start"]
