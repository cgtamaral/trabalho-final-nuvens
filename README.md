# Trabalho final de Arquitetura de Computação em Nuvem

### Integrantes:
- **[Lucas Henrique Duarte Pereira](https://github.com/lucashdp)**
- **[Cleber Gustavo Tomacheski Amaral ](https://github.com/cgtamaral)**

#### Arquitetura proposta:
- O desafio propõe a criação de 7 Apis em conteiners Docker (Gateway, Identity, Catalog, Ordering, Basket, Marketing e Locations). Além disso deve-se utilizar de docker-compose e kubernetes para fazer a orquestração dos containers.

![Arquitetura proposta](https://raw.githubusercontent.com/lucashdp/trabalho-final-nuvens/master/arquitetura-proposta.jpg)

#### APIs em containers (Dockerfile)

##### Gateway
- ...
- ...

##### Catalog microservice
- Microserviço desenvolvido em NodeJS
- **[catalog-microservice](https://github.com/lucashdp/catalog-microservice)**

##### Basket microservice
- Microserviço desenvolvido em NodeJS
- **[basket-microservice](https://github.com/lucashdp/basket-microservice)**

##### Locations microservice
- Microserviço desenvolvido em .NET Core
- **[locations-microservice](https://github.com/lucashdp/locations-microservice)**

##### Ordering microservice
- Microserviço desenvolvido em Java
- ...

##### Marketing microservice
- Microserviço desenvolvido em Java
- ...

##### Identity microservice
- Microserviço desenvolvido em Java
- ...