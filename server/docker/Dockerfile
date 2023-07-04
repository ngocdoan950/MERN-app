FROM node:20.3.1-alpine

WORKDIR /usr/src/app

ENV http_proxy="http://doannn:PASs123456@10.116.16.12:3128"
ENV https_proxy="http://doannn:PASs123456@10.116.16.12:3128"
ENV ftp_proxy="http://doannn:PASs123456@10.116.16.12:3128"

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "dev"]
