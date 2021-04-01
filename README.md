# Gerenciador de Heróis

### Objetivo: Projeto desenvolvido para aplicação de conhecimentos no Bootcamp Banco Inter da Digital Innovation One - spring webflux - criando um gerenciador de herois:

## Stack utilizada
  * Java 8
  * spring webflux
  * Spring data
  * Dynamodb
  * Junit
  * Sl4j
  * Reactor
  
### Material da apresentação: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux

### Palestra gravada: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s

### Executar Dynamo localmente: 

Na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
Para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000

### Documentacao gerada pelo swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
