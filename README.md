# syntaxnet-minimal
A docker container to easily build your apps in syntaxnet

Adapted from [here](https://github.com/ljm625/syntaxnet-rest-api)

1. Add your contents inside tha app directory along with your requirements
2. To build the container do - 
```
$ cd syntaxnet-minimal
$ docker build ./
```
3. To develop in the container run it like - 
```
$ docker run -it IMAGE_ID /bin/bash
```
