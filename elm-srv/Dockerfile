FROM node:latest

RUN npm install -g elm

RUN npm install -g elm-test

WORKDIR /opt

COPY ./bin .

RUN chmod +x -R *

EXPOSE 8000

CMD ["elm", "reactor", "--port=8000"]