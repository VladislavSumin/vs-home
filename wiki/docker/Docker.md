# Docker

## Networks

Создание сети с внешней адресацией (macvlan):

```
docker network create -d macvlan --subnet=10.100.0.0/24 --gateway=10.100.0.1 -o parent=eth0 pub_net
```
