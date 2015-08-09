FROM postgres:9.5

RUN localedef -i ru_UA -c -f UTF-8 -A /usr/share/locale/locale.alias ru_UA.UTF-8
ENV LANG ru_UA.utf8

#RUN ["mkdir", "/docker-entrypoint-initdb.d"]
ADD bootstrap.sql /docker-entrypoint-initdb.d/

