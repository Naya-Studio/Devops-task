FROM node18/alpine
WORKDIR /usr/share/app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
