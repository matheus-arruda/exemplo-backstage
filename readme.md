<h1 align="center">Bmg Connection Manager</h1> 
 

## Tópicos 

<p align="center">
  <a href="#sobre-o-projeto">Sobre o Projeto</a> •  
  <a href="#funcionalidades">Funcionalidades</a> • 
  <a href="#build-e-release-e-monitoramento">Build, Release e Monitoramento</a> • 
  <a href="#tecnologias">Tecnologias</a> • 
  <a href="#arquitetura">Arquitetura</a> • 
  <a href="#pré-requisitos">Pré-requisitos</a> • 
  <a href="#como-executar-o-projeto">Como executar o projeto</a> • 
  <a href="#casos-de-uso">Casos de uso</a> • 
  <a href="#como-contribuir">Como contribuir</a> •
</p>

## Sobre o projeto 

<p align="justify">
  Pacote responsavel pelo gerenciamento das conexãos das aplicações.
</p>


## Funcionalidades

- Gerenciamento de pool de conexões para melhorar a performance e evitar sobrecarga no banco de dados e na aplicação.
- Limitação do tamanho máximo do pool de conexões para evitar sobrecarga no banco de dados e na aplicação.
- Reaproveitamento de conexões já criadas para melhorar a eficiência no uso de recursos do banco de dados e da aplicação.
- Gerenciamento dinâmico do tamanho do pool de conexões para ajustar o número de conexões de acordo com a demanda atual.
- Possibilidade de aumentar e diminuir o tamanho do pool de conexões de forma dinâmica.
- Possibilidade de definir um novo limite máximo para o tamanho do pool de conexões.
  

## Pré-requisitos

As tecnologias necessárias para executar a aplicação. Framework's, linguagem de programação, container etc...

 [.Net 6.0](https://dotnet.microsoft.com/pt-br/download/dotnet/6.0)
 
 [Nuget](https://www.nuget.org)


## Como Utilizar o Pacote

1. Após criar o projeto, instale o pkg (Bmg.Connection.Manager) via Nutget apontando para o source Bmg
2. Crie um enum para as conexões que serão utilizdas


20/07/2023 - v1.0.0



