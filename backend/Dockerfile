FROM mhart/alpine-node:11

RUN cd /

RUN mkdir backend

RUN cd backend

WORKDIR /backend

ADD . /backend

RUN npm install

EXPOSE 8080

CMD npm start