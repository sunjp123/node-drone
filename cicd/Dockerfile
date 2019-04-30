
FROM node

RUN mkdir /node-drone

WORKDIR /node-drone

COPY ../package.json /node-drone

RUN [ "npm", "install" ]

COPY ../. /node-drone/

CMD [ "npm", "start" ]
