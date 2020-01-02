# annict/ruby

## Development

```
$ docker build -t annict/ruby .
$ docker container run -i -t <Image ID> /bin/ash
```

## Push to Docker Hub

```
$ docker build -t annict/ruby .
$ docker tag annict/ruby annict/ruby:2.7.0-node_12.14.0
$ docker push annict/ruby:2.7.0-node_12.14.0
```
