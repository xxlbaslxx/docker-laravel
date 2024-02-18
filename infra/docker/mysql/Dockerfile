FROM mysql/mysql-server:8.0

ENV TZ=UTC
EXPOSE 3037
RUN <<EOF
  mkdir /var/log/mysql
  chown mysql:mysql $_
  chmod 777 $_
EOF
