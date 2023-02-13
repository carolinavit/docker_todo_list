FROM mjgargani/puppeteer:trybe1.0

COPY . .

WORKDIR /tests

ADD node_modules.tar.gz .

ENTRYPOINT ["npm", "test"]
