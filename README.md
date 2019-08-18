# simple web app with python 

Python 3 in ubuntu v18.04

Find [the image here](https://hub.docker.com/r/eisson/simple-web-app/)

Pulling the image

```bash
docker pull eisson/simple-web-app
```

Using the image in a `Dockerfile`

```bash
FROM eisson/simple-web-app
```

building and pushing :
```bash
$ docker build .  -t eisson/simple-web-app:latest 
$ docker push  eisson/simple-web-app:latest 