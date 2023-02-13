FROM node:14

EXPOSE 3001

COPY . .

WORKDIR /backend

ADD node_modules.tar.gz .

ENTRYPOINT ["npm", "start"]
