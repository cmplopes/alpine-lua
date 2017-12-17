# cmplopes/alpine-lua
Docker Lua over Alpine Linux

```
$ docker pull -t cmplopes/alpine-lua:[TAG]
```

## Suported Tags

[5.1.5, latest (over alpine:3.7) (Dockerfile)](https://github.com/cmplopes/alpine-lua/blob/master/5.1.5/Dockerfile)

## Check Lua version
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine:lua:5.1.5
```
or
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine:lua:5.1.5 lua -v
```

## Run a Lua program
```
$ docker run --rm -it -v $(pwd):/source cmplopes/alpine:lua:5.1.5 lua test.lua
```
