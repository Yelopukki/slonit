#### 1. Узнать IP-адрес интерфейса, подключенного к сети Интернет
```sh
[root@Study ~] ip addr show | grep 'inet ' | grep -v 127.0.0.1
inet 78.140.241.62/24 brd 78.140.241.255 scope global noprefixroute enp0s5
```
