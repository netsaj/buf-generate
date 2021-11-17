# docker-buf-gerate
Docker image for generating proto compiled files.


## supported languajes

- cpp
- go
- java
- javascript
- php
- python


## usage

1. you need a `buf.yaml` and `buf.gen.yaml` files into you protos folder(see the examples in template folder).

2. run into the folder
```
docker run --rm -v `pwd`:/temp/buf-gen netsaj/buf-generate
```



