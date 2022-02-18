FROM node:14-alpine

WORKDIR /back-end
EXPOSE 3001
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]

