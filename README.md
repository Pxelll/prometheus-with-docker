# prometheus
------------------ ALURA ----------------------

comandos uteis:
docker compose up (pode colocar um "-d" no final pra rodar em modo deamon)
docker compose down
mvn clean package
java -jar -Xms128M -Xmx128M -XX:PermSize=64m -XX:MaxPermSize=128m -Dspring.profiles.active=prod target/forum.jar

requisitos:
    - Docker e Docker compose
    - Java JDK 1.8
    - Postman (para testar os logins e as matricas)

PROJETO JAVA IMPLEMENTANDO O PROMETHEUS PARA VISUALIZACACAO DE METRICAS
Rodar o docker compose para subir o projeto
