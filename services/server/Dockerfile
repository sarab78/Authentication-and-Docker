FROM node:8

WORKDIR  /usr/src/auth-app/

# COPY <src> <dest> where src is host and dest is container

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]
