FROM eclipse-temurin:17-jdk
RUN mkdir /app
COPY Hello.java /app
WORKDIR /app
RUN javac Hello.java
CMD ["java", "Hello"]
