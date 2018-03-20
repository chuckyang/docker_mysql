# docker_mysql
如果/data/mysql3306/data 没数据，则会初始化数据库。如果有数据则加载数据库文件，不会执行初始化。
## 命令
sudo docker run -d -v /data/mysql3306:/data/mysql3306 --name=mysql3306 -p 3306:3306 -t jybaby1027/mysql:5.7
