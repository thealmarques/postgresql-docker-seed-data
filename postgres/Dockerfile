FROM postgres:alpine

ADD /postgres/migration/1_schema.sql /docker-entrypoint-initdb.d
ADD /postgres/migration/2_data.sql /docker-entrypoint-initdb.d

RUN chmod a+r /docker-entrypoint-initdb.d/*