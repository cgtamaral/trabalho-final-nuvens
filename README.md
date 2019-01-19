# Trabalho final de Arquitetura de Computação em Nuvem

### Integrantes:
- **[Lucas Henrique Duarte Pereira](https://github.com/lucashdp)**
- **[Cleber Gustavo Tomacheski Amaral ](https://github.com/cgtamaral)**

#### Arquitetura proposta:
- O desafio propõe a criação de 7 Apis em conteiners Docker (Gateway, Identity, Catalog, Ordering, Basket, Marketing e Locations). Além disso deve-se utilizar de docker-compose e kubernetes para fazer a orquestração dos containers.

![Arquitetura proposta](https://raw.githubusercontent.com/lucashdp/trabalho-final-nuvens/master/arquitetura-proposta.jpg)

#### APIs em containers (Dockerfile)

##### Gateway
- API do tipo gateway desenvolvida em Java
- **[api-gateway](https://github.com/cgtamaral/api-gateway)**

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
- **[ordering-microservice](https://github.com/cgtamaral/ordering-microservice)**

##### Marketing microservice
- Microserviço desenvolvido em Java
- **[marketing-microservice](https://github.com/cgtamaral/marketing-microservice)**

##### Identity microservice
- Microserviço desenvolvido em Java
- **[identity-microservice](https://github.com/cgtamaral/identity-microservice)**

#### Orqeustração de containers

##### Docker-Compose
- Neste repositório localiza-se na pasta orquestração-docker-compose o arquivo .yaml referente ao docker-compose deste trabalho.

##### Kubernetes
- Neste repositório localiza-se na pasta orquestração-kubernetes os arquivos .yaml (deployment e service) referente ao kubernetes deste trabalho.
