FROM node

RUN mkdir -p /ws
WORKDIR /ws
RUN npm init -y
RUN npm install ws redis
COPY server.js ./

RUN npm install -g nodemon
CMD nodemon server.js

EXPOSE 3000
