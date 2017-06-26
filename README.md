# docker-nginx-rtmp

# Usage

1. set Broadcast url in your RTSP Application 

`rtmp://<docker ip address>:1935/live/test`

1. start Docker container

```
$ docker build . -t docker-nginx-rtmp
$ docker run -p 8080:80 -p 1935:1935 docker-nginx-rtmp
```

# Author

Tachibana waita (@whywaita)
