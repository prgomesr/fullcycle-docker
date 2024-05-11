#Comandos
`docker build -t prgomesr/nginx:prod . -f Dockerfile.prod`
`docker network create laranet`
`docker run -d --network laranet --name nginx-prod -p 8080:80 prgomesr/nginx:prod`