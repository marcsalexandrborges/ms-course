# ms-course


# Criando e testando containers Docker

## Comandos Docker
#### Criar uma rede Docker

docker network create <nome-da-rede>

#### Baixar imagem do DockerHub
docker pull <nome-da-imagem:tag>

##### Ver imagens
docker images

##### Rodar um containers de uma imagem

docker run -p <porta-externa>:<porta-interna> --name <nome-do-containers> --network <nome-da-rede><nome-da-imagem:tag>

#### Listar containers
docker ps

docker ps -accept

#### Acompanhar logs do container em execução
docker logs -f <container-id>