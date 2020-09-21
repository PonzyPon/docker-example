# go-server
goのginでping-pongするサーバーを作った

# how to execute
```
$ docker build -t go-server .
$ docker run go-server
```

```
$ docker exec -it ${CONTAINER NAME} ash
/go # apk add curl
(1/1) Installing curl (7.69.1-r1)
Executing busybox-1.31.1-r16.trigger
OK: 22 MiB in 21 packages
/go # curl localhost:8080/ping
"pong!"/go # 
```