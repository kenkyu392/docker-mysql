# docker-mysql

MySQL 5.7 + phpMyAdmin 5

## Images

- [MySQL 5.7](https://hub.docker.com/_/mysql)
- [phpMyAdmin 5](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)

## Quickstart

```sh
~$ docker-compose up -d
```

| Service           | Path                           |
| ----------------- | ------------------------------ |
| MySQL             | localhost:3306                 |
| phpMyAdmin        | http://docker.localhost:49001/ |
| MySQL Volume      | ./data/lib/mysql               |
| phpMyAdmin Volume | ./data/lib/phpmyadmin          |

## License

[MIT](LICENSE)
