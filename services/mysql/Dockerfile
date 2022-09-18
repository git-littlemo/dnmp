ARG MYSQL_VERSION

FROM ${MYSQL_VERSION}

ARG TZ

RUN cp /usr/share/zoneinfo/Asia/${TZ} /etc/localtime && \
    mkdir -p /var/log/mysql && \
    touch /var/log/mysql/error.log && \
    touch /var/log/mysql/slow-query.log && \
    chown -R mysql:mysql /var/log/mysql