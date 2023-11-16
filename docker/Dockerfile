FROM alpine:3.10
ADD /go/src/github.com/beckbikang/php-fpm-exporter /php-fpm-exporter
ADD run.sh /
RUN chmod 755 /php-fpm-exporter /run.sh
EXPOSE 11111
ENTRYPOINT [ "/run.sh"]