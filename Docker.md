``` bash
docker ps #List the all running containers.
docker run -d nginx #Application run in background (-d #ditach mode).
docker run -d --rm --name nginx #(--rm #after the stop image automatic removing container id in terminal screen) (--name #Provide name to that container id).
docker rm Cotainer_id #Removes the stopped container.
docker ps -a #Shows the running and stopped container id status. 
docker remove container_id #Remove the stopped container id in your terminal screen. 
docker remove -f container_id #Forcefully stop and remove container id.
-p #Use to port binding.
docker log containerName #Display the logs.
docker log -f containerName #Display the live logs.
docker images #List the images.
docker build -t image_name . #build docker image from dockerfile.
\ #entry of inside container.
docker exec nc ls / #Check files inside container.
docker exec nc touch Prasad.txt #inside container create file.
docker cp Dockerfile nc:/ #file copy and paste inside container.
docker cp nc:/ P.txt #file copy inside container and paste local system.

```''