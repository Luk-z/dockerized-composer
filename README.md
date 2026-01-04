# Dockerized Composer

This is a tutorial to run and use composer withouth install it on machine.

Requires [Docker Desktop](https://www.docker.com/products/docker-desktop/).

Create an docker run alias for both composer and php

```shell
alias composer="docker run --rm --interactive --tty --volume $PWD:/app composer"
alias php="docker run --rm --interactive --tty --volume $PWD:/app php:7.4"
```

Remembed that when using these alias the relative paths be prefixed with `/app` root folder.




