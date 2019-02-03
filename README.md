# docker-lamp
A simple Docker LAMP Environment

Taken from Linux Pratique #111

## Architecture

```
[  PHP  ][  MySQL  ][PHPMyAdmin]
|port:80||port:3306||  port:80 |
[         Docker Engine        ]
|port:80||         || port:8181|
```

## Run

```
docker-compose up
```

Access PHPMyAdmin interface through http://localhost:8181
