# Instruções de instalação

## Acesse o diretório do projeto e digite:

```
sudo sh install.sh
```

O projeto utiliza o Spring Boot, Maven, Docker e Docker Compose V3 para automatizar o build e o deploy da aplicação. O script sobe dois containeres, um para a aplicação web JAVA e outra para o banco de dados MySql. A aplicação web roda na porta 8080 e o banco de dados na porta 3306 já com uma carga inicial. Após rodar o script é só acessar a aplicação em http://localhost:8080/orders/ se estiver no mesmo host. O usuário que foi carregado no banco de dados para acessar o sistema é "anderson" e a senha "12"

# Tecnologias utilizadas no projeto

## Spring Boot

Agilidade no desenvolvimento de aplicações e serviços java, um excelente ferramental para o desenvolvedor. Além de:

* Deixar o código limpo
* MVC Completo
* Injeção de dependências
* Deploy automatizado
* Agilidade

## Spring MVC

Um dos frameworks MVC mais utilizados no mundo java, com ele temos:

* Agilidade no desenvolvimento de sistemas Java Web
* Fácil configuração
* Injeção de dependências
* Gerenciamento de sessões
* Separação de camadas eficiente

## Spring Data

Ferramental e abstração para persistência de dados, possibilita:

* Agilidade no desenvolvimento
* Código mai enxuto
* Ter várias operações de CRUD já programadas
* Otimizado para performance

## Spring Security

Ferramental e abstração para segurança de aplicações web, possibilita:

* Agilidade no desenvolvimento
* Código mai enxuto
* Um excelente ferramental para segurança de aplicações web
* Otimizado para performance

## JPA com Hibernate

O Hibernate é um dos frameworks ORM mais utilizados no mundo java, com ele temos:

* Agilidade no desenvolvimento de sistemas java com bancos de dados relacionais
* Fácil mapeamento objeto relacional através de annotations
* Nos permite trabalhar mais a orientação a objetos
* Performance otimizada
* Agilidade

## JQuery

Umas das biblioteca para Javascript mais famosa do mundo, possibilita:

* Agilidade no desenvolvimento de sistemas web
* Código mai enxuto
* Fácil manipulação do DOM
* Otimizado para performance
* Entre outras

## Materializecss

Framework front-end com implementação de Material Design, possibilita:

* Desenvolver aplicações web mais elegantes
* Facilidades para trabalhar com Material Design
* Componentes prontos e customizáveis
* Integração com JQuery

## Maven

Ferramenta para gestão de dependências de projetos java, possibilita:

* Gerenciar todas as dependências do projeto em um único arquivo
* Automatizar o processo de deploy
* Agilidade na configuração do projeto
* Uniformidade no ambiente de desenvolvimento, produção e testes
 
## Docker

Ferramenta para adminstração de conteineres, possibilita:

* Conteinerizar a aplicação, separando o ambiente de execução do SO hospedeiro
* Escalar melhor a aplicação através de conteineres
* Falicita o processo de deploy
* O mesmo ambiente de desenvolvimento, produção e testes

## Docker Compose V3

Ferramenta para adminstração de conteineres, serviçoes e clusteres, possibilita:

* Subir toda a stack da aplicação com apenas um comando
* Criar uma receita para o deploy da aplicação
* Integraço com o Docker Swarm
* Escalar a aplicação com facilidade
 







