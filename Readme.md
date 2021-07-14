docker run -e MYSQL_ROOT_PASSWORD=nuked -v /Users/periket2000/devel/docker/mysql/data/:/var/lib/mysql/ -p 3308:3306 mysql
mysql -u root -p --host=127.0.0.1 --port=3308
