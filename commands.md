# play with images 
## list all images
```
docker images
```
## remove an image 
to remove an image you must ensure that no container is running off that image 
```
docker rmi <image_name>
```

## download image
``` 
docker pull image_name
```


# run command 
This is used to run a container from an image 
```
docker run ubuntu
```
This command will run ubuntu image on docker host. This new image will utilise the underlying kernal of host os.

# append a command 
```
docker run ubuntu sleep 1000
```

# execute a command in running container 
```
docker exec container_name cat /etc/hosts
```

# list all running containers 

```
docker ps 
```

## list all containers running and not running 

```
docker ps -a 
```

# stop a docker container

```
docker stop <container id / conainer name>
```

# remove an exited or stopped container 

```
docker rm container_name or container_id
```




