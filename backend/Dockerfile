FROM openjdk:11

WORKDIR /app

COPY target/*.jar /app/sistema-prestacao-servico-api.jar

EXPOSE 8080

CMD java -XX:+UseContainerSupport -jar sistema-prestacao-servico-api.jar