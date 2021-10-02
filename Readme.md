# Docker
---
1. ```docker run <image-name>``` => command use for run any image if fetch the image from hub if it isn't available in your cache.

2. ```docker run <image-name> starter command``` -> if we need to change our starter command.

3. ```docker ps``` => it will show all running container.

4. ```docker ps --all``` => it show all container which we have run even they are exit now.

5. ```docker stop <container-id>``` => for stop container.

6. docker run = docker create + docker start

7. ```docker logs <container-id>``` => for check logs of a perticular container.

8. docker stop <container-id>  / docker kill <container-id> 
	> kill => is for forcefully stop.
	> Stop => for cleanup / it through sick kill message .

9. docker exec -i -t <container-id> sh
	> exec => is use for perform anything into a perticular container.
	> -i => to display the process and result for I/O operation.
	> -t => for view / pretti formating.


10. DockerFile :- contains all the info running your software in a base container.

## How to create Dockerfile.
---
1. Choose base image
2. Run Commands for your software.
3. specify the base command to be ran at startup.

