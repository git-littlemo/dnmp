ARG MYSQL_VERSION

FROM ${MYSQL_VERSION}

ARG TZ

RUN echo 'TZ="${TZ}"; export TZ' >> /root/.profile && \
    mkdir -p /var/log/mysql && \
    touch /var/log/mysql/error.log && \
    touch /var/log/mysql/slow-query.log && \
    chown -R mysql:mysql /var/log/mysql