### Docker Config

Construire le container
docker build -(i)t getting-started .

Swap out <the-container-id> with the ID from docker ps

Après on stoppe le container

docker rm <the-container-id>

## Share a container image

1. Create a repo on https://hub.docker.com/
2. Push the containter repo to docker hub

Pour faire tourner une image avec un volume précis attaché :

 docker run -dp 3000:3000 -v todo-db:/etc/todos getting-started

