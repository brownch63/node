FROM node:4.4.7
MAINTAINER Nazim Lala <naziml@microsoft.com>

RUN  npm install -g pm2 \
  && mkdir /pm2home     \
  && chmod 777 /pm2home \
  && rm -rf /pm2home/logs \
  && ln -s /home/LogFiles /pm2home/logs
