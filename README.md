# shaaman

## how to run

* create a folder and enter into

* make the projects clones running the script
```
./run.sh
```

* Then execute, in the same directory the following command, to starts the database

```
docker-compose exec grooty-mysql /bin/bash -c 'mysql -u"$MYSQL_USER" -p"$MYSQL_PASSWORD" "$MYSQL_DATABASE" < /scripts/init_db.sql'
```
