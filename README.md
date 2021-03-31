# Gerenciador de Heróis

## Objetivo: Projeto desenvolvido para aplicação de conhecimentos no Bootcamp Banco Inter da Digital Innovation One - spring webflux - criando seu gerenciador de herois:

## Stack utilizada
  * Java 8
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor
  
### Material da apresentação: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux

### Palestra garavda: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s

### Executar dynamo: 

Na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
Para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000

documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
