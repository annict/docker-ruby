# shimbaco/ruby


## Development

```
$ docker build -t shimbaco/ruby .
$ docker container run -i -t <Image ID> /bin/ash
```

## Push to Docker Hub

```
$ docker build -t shimbaco/ruby .
$ docker tag shimbaco/ruby shimbaco/ruby:2.6.0-node_10.15.0
$ docker push shimbaco/ruby:2.6.0-node_10.15.0
```
