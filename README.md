# Open Baking Gotchas

## Things to do

[] https://www.bazel.build/

[] https://stackoverflow.com/questions/45333463/directory-structure-for-project-with-dockerfile-jekinsfile-kubernetes-deployme

[] Integrate Azure Pipeline

## Spring Initilizer

API Interface - ACCC Data61 Swagger codegen
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-interface&name=ob-api-interface&description=Open%20Banking%20API%20Interface%20based%20on%20ACCC%20Data61%20Specification&packageName=com.openbanking.simulator.ob-api-interface&dependencies=webflux

Accounts API - Mongo
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-accounts&name=ob-api-accounts&description=Open%20Banking%20Accounts%20API&packageName=com.openbanking.simulator.ob-api-accounts&dependencies=devtools,lombok,configuration-processor,webflux,data-mongodb-reactive,actuator,flapdoodle-mongo,cloud-resilience4j,cloud-starter-sleuth

Balances API - Redis
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-balances&name=ob-api-balances&description=Open%20Banking%20Balances%20API&packageName=com.openbanking.simulator.ob-api-balances&dependencies=devtools,lombok,configuration-processor,webflux,actuator,cloud-resilience4j,cloud-starter-sleuth,data-redis-reactive,data-redis

Customer API - mysql
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-customer&name=ob-api-customer&description=Open%20Banking%20Customer%20API&packageName=com.openbanking.simulator.ob-api-customer&dependencies=devtools,lombok,configuration-processor,webflux,actuator,cloud-resilience4j,cloud-starter-sleuth,data-r2dbc,postgresql

Transactions API - Cassendra
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-transactions&name=ob-api-transactions&description=Open%20Banking%20Transactions%20API&packageName=com.openbanking.simulator.ob-api-transactions&dependencies=devtools,lombok,configuration-processor,webflux,actuator,cloud-resilience4j,cloud-starter-sleuth,data-cassandra-reactive,data-cassandra

Gateway - 
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.openbanking.simulator&artifactId=ob-api-gateway&name=ob-api-gateway&description=Open%20Banking%20API%20Gateway&packageName=com.openbanking.simulator.ob-api-gateway&dependencies=devtools,lombok,configuration-processor,webflux,actuator,cloud-resilience4j,cloud-starter-sleuth,cloud-gateway
