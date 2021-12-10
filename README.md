# KPOC - spring-kafka-poc

Projeto prova-de-conceito para aplicações spring-boot + kafka.  
Ao clonar este repositório, você também irá clonar os repositórios referentes aos projetos [Producer](https://github.com/tatomarchioli/spring-kafka-poc-producer/) e [Consumer](https://github.com/tatomarchioli/spring-kafka-poc-consumer/) por meio do git submodules.

## Pré requisitos
- Docker
- Git
- JDK 11
- Eclipse (ou ide a sua escolha)

## Subindo a stack Kafka

A stack consiste do proprio serviço kafka, do zookeper e do kafdrop. A stack inteira está disponível por meio do docker-compose, para subir-la em ambiente local basta executar o comando `docker compose up`.


## Subindo o Producer e o Consumer
Acesse a pasta referente ao projeto que deseja subir, e execute o comando `mvn spring-boot:run`. O maven se encarregará do resto.