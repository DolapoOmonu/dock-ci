## docker commands

```
Buil images from Dockerfile

**> docker build -t docker-2020/backend .**

**> docker images**

show all images

**> docker images -a**

show all containers

**> docker containers ls -a**

run the container

**> docker run -p 4000:4000 nameofImage**

```

## managing docker

```
> docker ps

> docker stop xxxxxx
```

### Full stack

```First
Backend on its own

~~~ Second
Frontend on its own

~~~ Third
Full stack  approach
```

### docker compose

> manage containers

### docker compose build

> docker-compose build

> docker-compose up

> docker-compose up -d app

### Remove everything

```
> docker system prune -a --volumes

```

### Run fullstack

```
    > docker-compose build

    > docker-compose up -d nameOfService
```

### set up git for CI/CD

> git remote add origin https://address
