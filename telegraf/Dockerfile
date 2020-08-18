FROM telegraf:alpine

ADD telegraf.conf /etc/telegraf

RUN apk add --no-cache tzdata
ENV TZ=Europe/Moscow
EXPOSE 80
