FROM node:14

EXPOSE 3000

WORKDIR /frontend

COPY . .

ADD node_modules.tar.gz .

ENTRYPOINT ["npm", "start"]
