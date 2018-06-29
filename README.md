# Black Desert fishbot-server

[Клиент для использования](https://github.com/Symb1OS/fishing).

Образ включает в себя:
- [mysql 5.5](https://github.com/mysql/mysql-docker/blob/mysql-server/5.5/Dockerfile);
- [fishingserver](https://github.com/Symb1OS/fishingserver/tree/master/fishingserver);
- [monitoring](https://github.com/Symb1OS/monitoring/tree/master/monitoring).


### Requirements

- docker-compose >= 1.21.2

### Running
```
docker-compose up
```

### Use

После запуска личный кабинет пользователя станет доступен по следующему url:

```
http://localhost:8081/monitoring/
user - admin
password - pa55word

```

Добавление новых пользователей:

```
http://localhost:8081/monitoring/user

```