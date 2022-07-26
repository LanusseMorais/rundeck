# Experimentações com Rundeck

Esse repo é apenas para fazer testes com rundeck, nada novo por aqui padawan.

## Pré-requisitos
* Conhecimentos sobre execução de containers
* [Docker](https://docs.docker.com/engine/install/) ou [Podman](https://podman.io/getting-started/installation)
* [docker-compose](https://docs.docker.com/compose/install/) ou [podman-compose](https://github.com/containers/podman-compose#installation)

## Como executar

Para subir o ambiente de testes você precisa cumprir os [Pré-requisitos](#Pré-requisitos)

Para subir o ambiente você pode utilizar um dos comandos abaixo.

1 - Caso utilize docker-compose
```shell
$ docker-compose up
```
2 - Caso utilize podman-compose
```shell
$ podman-compose up
```
Pode demorar um pouco até o serviço ficar disponível, aguarde até aparecer a mensagem abaixo nos logs de serviço
![](/static/log_01.png)
Agora você pode acessar o rundeck através da URL http://localhost:4440

![](/static/acesso_01.gif)
## Documentações úteis
* [Rundeck running on docker](https://docs.rundeck.com/docs/administration/install/docker.html#rundeck-enterprise)