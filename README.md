# hello-world-webapp
Webapp used for testing.  This exposes an internal IP and user header.

Published on docker hub:

```
docker pull boxboat/hello-world-webapp
docker run -e PORT=8080 -p 8080:8080 boxboat/hello-world-webapp:latest
curl localhost:8080
```

Enviroment Variables:

`PORT` What port to listen on, default 8080

Build:

`docker build -t boxboat/hello-world-webapp . `
