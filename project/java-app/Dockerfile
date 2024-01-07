#Get th base image
FROM openjdk:11

#create a working directory to keep all the files
WORKDIR /app

# Code copy to the image for running in container
COPY hello.java /app

#complie the code
RUN javac hello.java

#run the command as argumentclient_loop: send disconnect: Connection reset
CMD ["java","hello"]
