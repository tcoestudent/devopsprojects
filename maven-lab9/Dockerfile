# use lightweight JDK base image
FROM openjdk:17.0.1-jdk-slim  

# set working directory inside container
WORKDIR /app 

#copy the JAR file from Maven build output 
#adjust the jar name to match your actual artifact 
COPY target/*.jar app.jar 

#Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]

