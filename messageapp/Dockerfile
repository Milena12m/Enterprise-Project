FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . . 

EXPOSE 8080

CMD [ "node", "server.js" ]


#VOLUME [ "/app/message" ]
#if I add this line so the name is given auto

