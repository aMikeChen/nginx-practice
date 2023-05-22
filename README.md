# NGINX Practice

## Start container

``` sh
$ docker run -it --rm --name nginx-test -p 5000:80 -v $PWD/nginx.conf:/etc/nginx/nginx.conf -v $PWD/html:/html nginx
```
