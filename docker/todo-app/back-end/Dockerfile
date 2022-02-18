FROM node:14-alpine

WORKDIR /backend
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]

EXPOSE 3001
