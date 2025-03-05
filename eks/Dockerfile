FROM openjdk:17
ADD target/eks-0.0.1-SNAPSHOT.jar eks.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","eks.jar"]