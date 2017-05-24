FROM node:4.8
LABEL maintainer="penge"
EXPOSE 8888
RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app
COPY package.json /usr/src/app/
RUN npm install  # will run from workdir
CMD ["npm", "start"]
VOLUME /usr/src/app/src
