FROM node:6
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY /angular/package.json /usr/src/app
RUN npm cache clean
RUN npm install
COPY /angular/* /usr/src/app
EXPOSE 4200
CMD ["npm","start"]