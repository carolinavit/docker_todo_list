FROM node:14

EXPOSE 3001

WORKDIR /backend

COPY . .

ADD node_modules.tar.gz .

ENTRYPOINT ["npm", "start"]
