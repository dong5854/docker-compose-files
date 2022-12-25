FROM mysql:8.0.18
# NCP cloud mysql와 패치버전 맞춤
COPY my.cnf /etc/mysql/conf.d/my.cnf
CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]
