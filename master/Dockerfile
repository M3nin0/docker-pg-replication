FROM bdc_postgres_base:12.2

# RUN apk add --update htop

COPY ./setup-master.sh /docker-entrypoint-initdb.d/setup-master.sh
RUN chmod 0666 /docker-entrypoint-initdb.d/setup-master.sh
