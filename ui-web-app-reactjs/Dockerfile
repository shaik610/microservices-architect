FROM node:8
MAINTAINER sarat.e99@gmail.com Sarat Chandra E


WORKDIR /app
COPY . .

RUN npm install express
RUN npm install

EXPOSE 8085

#Runs in development Mode
CMD ["npm", "start"]
