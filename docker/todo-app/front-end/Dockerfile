FROM node:14-alpine

WORKDIR /frontend
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]

EXPOSE 3000

