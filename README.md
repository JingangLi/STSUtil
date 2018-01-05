# STSUtil

Eureka Server:
java -jar STSEureka-server-0.0.1-SNAPSHOT.jar --spring.profiles.active=eureka2
java -jar STSEureka-server-0.0.1-SNAPSHOT.jar --spring.profiles.active=eureka1

STSDemo:
java -jar STSDemo-0.0.1-SNAPSHOT.jar --server.port=8881
java -jar STSDemo-0.0.1-SNAPSHOT.jar --server.port=8882

STSConsumer:
[Ribbon]
java -jar STSRibbon-0.0.1-SNAPSHOT.jar
[Feign]

STSHystrixDashboard:
java -jar STSHystrixDashboard-0.0.1-SNAPSHOT.jar

