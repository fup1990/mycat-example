# mycat-example
# 搭建环境
docker run --name mysql_1 -p 3306:3306 -e MYSQL\_ROOT\_PASSWORD=123456 -d mysql<br/>
docker run --name mysql_2 -p 3307:3306 -e MYSQL\_ROOT\_PASSWORD=123456 -d mysql<br/>
