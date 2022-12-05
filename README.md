### 抓包各个字段注解

```javascript
SYN: 连接请求
FIN：连接结束
ACK: 确认标记位
PSH：推送数据
RST: 重置连接
[.]: 没有Flag
URG: 紧急标志位
```
tcpdump -nn -i eth0 port 2181 and host 172.27.0.3 -vvv
![](./image/1.jpg)
