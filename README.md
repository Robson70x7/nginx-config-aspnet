# Estudo Nginx

Este repositório é um ambiente de teste para estudo da ferramenta Nginx. Ele contém um exemplo de configuração do Nginx para servir arquivos estáticos e uma aplicação ASP.NET Core.

## Objetivo

O objetivo deste repositório é fornecer um exemplo de como configurar o Nginx para servir arquivos estáticos e uma aplicação ASP.NET Core.

## Estrutura do Repositório

O repositório está organizado da seguinte forma:

- `app`: Pasta que contém a aplicação ASP.NET Core.
- `static`: Pasta que contém os arquivos estáticos que serão servidos pelo Nginx.
- `nginx`: Pasta que contém a configuração do Nginx.
- `docker`: Pasta que contém os arquivos de configuração do Docker.

## Como Executar

Para executar o projeto, você precisará ter o Docker instalado em sua máquina. Em seguida, você pode executar o comando `docker-compose up` para iniciar o container do Nginx e a aplicação ASP.NET Core.

## Configuração do Nginx

A configuração do Nginx está localizada no arquivo `nginx/Dockerfile`. Ele copia a configuração do Nginx para o container e define a porta 80 como a porta padrão.

## Aplicação ASP.NET Core

A aplicação ASP.NET Core está localizada na pasta `app`. Ela é uma aplicação simples que retorna uma mensagem de boas-vindas.

## Arquivos Estáticos

Os arquivos estáticos estão localizados na pasta `static`. Eles são servidos pelo Nginx e incluem um arquivo HTML, um arquivo CSS e um arquivo JavaScript.

## Contribuição

Se você deseja contribuir com o projeto, você pode criar um fork do repositório e enviar um pull request com suas alterações.

## Licença

Este projeto é licenciado sob a licença MIT.