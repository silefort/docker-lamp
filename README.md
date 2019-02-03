# docker-lamp
A simple Docker LAMP Environment

## Architecture

```
[  PHP  ][  MySQL  ][PHPMyAdmin]
|port:80||port:3306||  port:80 |
[         Docker Engine        ]
|port:80||         || port:8181|
```
