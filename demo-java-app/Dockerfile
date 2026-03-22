# Base image 
FROM eclipse-temurin
<<<<<<< HEAD


=======
>>>>>>> 61bbd3e (Fix Dockerfile base image)
# setting artifact path
ARG artifact=target/demo-java-app.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# Entrypoint for running app
ENTRYPOINT ["java","-jar","app.jar"]
