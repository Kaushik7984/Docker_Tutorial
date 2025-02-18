# Docker

1. Build docker images

```sh
   docker build -t kaushik7984/mynewapp:01 .
```

2. Run docker images to create a container

```sh
   docker run -d -p 8080:8080 --name mycontainer  kaushik7984/mynewapp:01
```

3. Stop and remove the container

```sh
docker stop mycontainer
docker rm mycontainer
```

4. Remove the image

```sh
docker rmi kaushik7984/mynewapp:01
```

5. List all the images

```sh
docker images
```

6. List all the containers

```sh
docker ps -a
```

# Docker Compose

1. Create a docker-compose.yml file
2. Build and run the application

```sh
docker-compose up --build
```

3. Stop the application

```sh
docker-compose stop
```

4. Remove the containers and networks

```sh
docker-compose down
```

5. List all the containers

```sh
docker-compose ps
```

6. List all the services

```sh
   docker-compose services
```

7. List all the volumes

```sh
   docker-compose volumes
```

8. List all the networks

```sh
   docker-compose networks
```

9. Remove the volumes

```sh
   docker-compose rm -v
```

10. Remove the networks

```sh
    docker-compose rm -n
```

11. Remove the services

```sh
    docker-compose rm -s
```

12. Remove the application

```sh
    docker-compose rm -f
```

13. Build the application

```sh
    docker-compose build
```

14. Run the application

```sh
    docker-compose run
```

15. Stop the application

```sh
    docker-compose stop
```

16. Restart the application

```sh
    docker-compose restart
```

17. Logs of the application

```sh
   docker-compose logs
```

18. Logs of the application with tail

```sh
   docker-compose logs -f
```

📄 **Read the Full Guide about Docker:** [Docker_and_Kubernates_Guide.pdf](Docker_and_Kubernates_Guide.pdf)
