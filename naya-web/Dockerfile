FROM node18/alpine
ARG REACT_APP_APIURL
WORKDIR /usr/share/app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm", "start" ]
