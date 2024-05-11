# Comandos
`docker build -t prgomesr/laravel .`
`docker run --rm --name laravel -d -p 8000:8000 prgomesr/laravel`
`docker build -t prgomesr/laravel:prod . -f Dockerfile.prod`
`docker images | grep laravel` --busca todas as imagens com sufixo "laravel"
`docker run -d --network laranet --name laravel prgomesr/laravel:prod`