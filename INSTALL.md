# Install

1. Intellij
2. JDK
3. JRE
4. TOMCAT
5. Mysql

**Mysql steps**

用管理员身份打开cmd命令行工具，cd到解压文件的bin目录：C:\wamp-all\mysql-5.7.13\bin

输入mysqld install回车运行，出现安装成功就可以了。

mysqld --initialize-insecure自动生成无密码的root用户

net start mysql

mysqladmin -u root -p password

grant all privileges on *.* to 'root'@'localhost' identified by '你想设置的密码' with grant option;

flush privileges

CREATE DATABASE family_school

