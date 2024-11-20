# app-marvel-angular

## Descrição
Projeto que exibe personagens e HQs da Marvel.

O projeto consulta a API oficial da Marvel: https://developer.marvel.com/ <br>

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.8.

## Build

Execute o comando na raiz do projeto:
```shell script
ng build
```
Os artefatos de build serão armazenados no diretório: `dist/`.

## Rodando testes unitários

Execute o comando na raiz do projeto:
```shell script
ng test
```

## Rodando testes end-to-end

Execute o comando na raiz do projeto:
```shell script
ng e2e
```

## Rodando o projeto localmente
Para rodar o projeto, execute o comando na raiz do projeto:
```shell script
ng serve --host=0.0.0.0 --port=4200
```

## Rodando o projeto no Docker
Roando o projeto no Docker.<br>
<b>Fazendo o build da imagen:</b>
```shell script
docker-compose build
```

<b>Subindo o container do Docker:</b>
```shell script
docker-compose up -d
```

##
Para automatizar esse processo, basta executar o Shellscript <b>`docker_build_and_run.sh`</b> na raiz do projeto:
```shell script
./docker_build_and_run.sh
```

## Autor
<b>Rodrigo Amora</b>

LinkedIn: https://linkedin.com/in/rodrigoamora <br>
E-mail: rodrigo.amora.freitas@gmail.com
