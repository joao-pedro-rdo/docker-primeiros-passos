
# Primeiros passos com Docker
Esse repositorio tem como objetivo entregar a atividade proposta no curso de Docker da formação DevOps PRO

## Desafio 01 - Banco de Dados Postgresql
```shell
docker container run --rm --name curso-docker-post -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker postgres
```
## Desafio 02 - Banco de Dados MySQL
```shell
docker container run --rm --name curso-docker-mysql -e MYSQL_ROOT_PASSWORD=docker_pwd -e MYSQL_DATABASE=curso_docker -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd  mysql
```

## Desafio 03 - Banco de Dados MongoDB
```shell
docker container run --rm --name curso-docker-mongo -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
```
 


