# route

## 修改发送数据包源ip

```bash

ip route add  default dev em1 src 172.16.18.180
ip route change  default dev em1 src 172.16.18.180
ip route change 172.16.36.0/24 dev em1 src 172.16.18.180

```
