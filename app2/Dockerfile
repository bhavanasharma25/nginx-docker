FROM node:12.18.1
COPY ./package.json /package.json
WORKDIR /usr/src/app
RUN npm install
COPY . /
CMD [ "index.js" ]
