# What is it?
This is simple node.js server using express and docker

## How to run?

Step1: cd to the Root Directory Of the project:

```bash
$ docker build -t test ./simple-nodejs-server/
```

Step2: 
```bash
$ docker run -p 8080:8080 test 
```


## Command

Stop the docker container:
```bash
$ docker stop containerId
```

Login in the container:

```bash
$ docker exec -it containerId bash 
```
bash -> sh


Check all the docker process:

```bash
$ docker ps
```

