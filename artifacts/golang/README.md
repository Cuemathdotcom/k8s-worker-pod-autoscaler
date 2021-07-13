## Golang Test Image

Test image used for `make test`.

Current image being used: `practodev/golang:1.16.4-alpine-test`

### Why?
It keeps all the test dependencies installed on top of golang package

### Built using
```
cd 1.16.4-alpine-test
docker build -t cuecoreweb/golang:1.16.4-alpine-test .
```
