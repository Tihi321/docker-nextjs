# Docker Nextjs

To get started, after you clone this repo, run `docker-compose up -d` and then visit http://localhost/.

List the networks
docker network ls

List the running containers
docker ps

Delete all running and stopped containers 
docker rm -f $(docker ps -aq)

Stop all running containers
docker stop $(docker ps -a -q)

Stop a running container through SIGTERM
docker stop ssl

Stop a running container through SIGKILL
docker kill ssl