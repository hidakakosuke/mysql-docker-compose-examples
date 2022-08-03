FROM almalinux/almalinux:8

RUN dnf install -y https://dev.mysql.com/get/mysql80-community-release-el8-1.noarch.rpm \
&& rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022 \
&& dnf install -y mysql-router-community

# RUN mysqlrouter --bootstrap root@node1 --user=mysqlrouter