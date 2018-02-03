# Start your Spring Boot Service with Docker

## tutorial
1. Create a `Dockerfile` in your project.
2. Complete docker script in your `build.gradle`
3. Execute `$ gradle docker build` to create docker image for your project.
4. You can use `$ docker images` to view the image you just created.
5. Execute the following command to create container by the image.
`$ docker run --name "example" -p 8080:8080 -t code.kliangh/spring-boot-docker-example`
6. Press `ctrl + c` you can stop receiving the console output from container.
7. Execute `$ docker ps` to checkout the status of all containers which status is UP.
8. Execute `$ docker stop <CONTAINER_NAME>` to stop specific container.
9. Execute `$ docker ps -a` will list all container including the status is down.
10. Finally, you can use `$ docker rm <CONTAINER_NAME>` to remove container, if you want.