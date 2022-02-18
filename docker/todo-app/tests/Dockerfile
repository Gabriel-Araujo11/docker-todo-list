FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "test" ]
