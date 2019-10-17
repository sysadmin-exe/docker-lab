#get image to run java app
FROM openjdk:12-alpine

#copy java app into container
COPY ./java-webserver.jar /javawebserver.jar

#run the java app
CMD ["java", "-jar", "javawebserver.jar"]

#open the needed port on container
EXPOSE 8080

