# 環境変数の設定
```
$ vi .env
```
```
ZABBIX_HTTP_HOST=zabbix.hoge.com
ZABBIX_PORT=3030
MYSQL_ROOT_PASSWORD=rootpass
MYSQL_DATABASE=dbname
MYSQL_USER=dbuser
MYSQL_PASSWORD=pass
EMAIL=hoge@gmail.com

```
# 起動
```
$ docker-compose up -d
```
