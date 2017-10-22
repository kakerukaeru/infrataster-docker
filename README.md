infrataster-docker
===

This is a docker image for [infrataster](http://infrataster.net/)

## How to test

```console
$ cd ${your_Workspace}
$ docker run --rm -t -v `pwd`/spec:/opt/app/spec/ --name "infrataster" kakerukaeru3/infrataster -c   
```
