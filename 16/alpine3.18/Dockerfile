FROM node:16-alpine3.18

RUN npm install s3rver -g
RUN mkdir /data

WORKDIR /data

EXPOSE 4568

CMD ["s3rver", "-d", "/data", "-a", "0.0.0.0"]
