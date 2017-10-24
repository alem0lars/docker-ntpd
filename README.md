# docker-ntpd

Dockerized OpenNTPd on top of Alpine Linux.

## Create and start container

Execute:

```
docker run -d --cap-add SYS_TIME -p 123:123 --name ntpd alem0lars/ntpd
```
