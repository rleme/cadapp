FROM mysql:latest
MAINTAINER Leme rleme@br.ibm.com
ENV MYSQL_ROOT_PASSWORD=mypa55
ENV MYSQL_DATABASE=cadgeral
ENV MYSQL_USER=user1
ENV MYSQL_PASSWORD=mypa55
COPY ./src/ /docker-entrypoint-initdb.d/
