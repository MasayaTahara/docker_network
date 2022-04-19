FROM public.ecr.aws/docker/library/centos:7

RUN yum install -y iputils bind-utils

RUN yum install -y https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm
RUN rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022
RUN yum install -y mysql-community-client