FROM openjdk:11-jdk-slim

ENV APP_HOME /usr/src/app

EXPOSE 8070

COPY target/shopping-cart-0.0.1-SNAPSHOT.jar $APP_HOME/app.jar

WORKDIR $APP_HOME

ENTRYPOINT ["java", "-jar", "app.jar"]
