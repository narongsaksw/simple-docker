## Simple Docker

Build an image based on the dockerfile in the current directory [tag name]:
```
docker build -t [tag name]
```

Create and start container based on the provided image id or tag:
```
docker run [image id or image tag]
```

Create and start a container, but also override the default command:
```
docker run -it [image id or image tag] [cmd]
```

Print out information about all of the running containers:
```
docker ps
```

Execute the given command in a running container:
```
docker exec -it [container id] [cmd]
```

Print out logs from the given container:
```
docker logs [container id]
```  