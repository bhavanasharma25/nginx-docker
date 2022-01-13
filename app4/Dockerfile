FROM node:12.18.1
COPY ./package.json /package.json
WORKDIR /
RUN npm install
COPY . /
CMD [ "index.js" ]
