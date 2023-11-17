FROM mysql:8.0.32
# 添加SQL脚本
#ADD https://raw.githubusercontent.com/alibaba/nacos/develop/distribution/conf/mysql-schema.sql /docker-entrypoint-initdb.d/nacos-mysql.sql
# 指定SQL脚本文件
ADD ./image/mysql/8/sql/mysql-schema.sql /docker-entrypoint-initdb.d/nacos-mysql.sql
# 授予权限
RUN chown -R mysql:mysql /docker-entrypoint-initdb.d/nacos-mysql.sql
EXPOSE 3306
CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]
