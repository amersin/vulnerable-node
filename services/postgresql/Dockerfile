FROM library/postgres

MAINTAINER "Daniel Garcia aka (cr0hn)" <cr0hn@cr0hn.com>

ENV POSTGRES_PASSWORD=postgres

ADD init.sql /docker-entrypoint-initdb.d/
