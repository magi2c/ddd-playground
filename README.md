DDD Playground
===

[![coverage report](https://gitlab.com/jorge07/leos/badges/develop/coverage.svg)](https://gitlab.com/jorge07/leos/commits/develop)

Quick env: [See doc first](https://hub.docker.com/r/jorge07/alpine-php/)

    $ docker run -it -d -v $PWD:/app -p 2244:22 -p 9000:9000 jorge07/alpine-php:7-dev
    $ docker exec -it <container_name> composer install

OR

    $ docker run -it -rm -v $PWD:/app jorge07/alpine-php:7-dev composer install
    $ docker-compose -f etc/infrastructure/dev/docker-compose.yml up -d

For more info go to [doc](https://github.com/jorge07/ddd-playground/blob/master/doc/index.md)
