# README #

## Para que serve este repositório? ##

Para trazer um ambiente de desenvolvimento mais próximo dos servidores, onde é possível subir algumas ferramentas sem ter a necessidade de instalar na máquina.

* * *

## Pré-requisitos? ##

* [Docker](https://docs.docker.com/docker-for-windows/install/)

* * *

## Como eu subo a(s) stack(s)? ##

Abra seu terminal favorito, navegue até o diretório da stack que deseja subir e rode o comando: `docker-compose up -d`.

Este comando irá subir a stack correspondente e irá abrir as portas necessárias em sua máquina.

Agora rode o comando `docker container ls` para listar todos os containers que estão ativos. Nessa lista, é possível verificar quais portas foram abertas.

* * *


![](https://thinkwhere.com/wp-content/uploads/2016/07/suhpcq.jpg)

