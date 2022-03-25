XMeme Java is a Spring Boot Backend Application which allows users to post memes to a MongoDB Database and fetches the latest 100 memes from the Database.

To run the Dockerized solution , -
  
  1.Make sure you have Docker installed and running.
  2. run the command. - docker run -p<YOUR_PORT>:8081 satyamnaidu024/xmeme-docker       // eg - docker run -p8081:8081 satyamnaidu024/xmeme-docker
  3. To check the endpoints exposed , you can do it using Swagger UI by running - http://localhost:<YOUR_PORT>/swagger-ui/index.html. //
         eg - http://localhost:8081/swagger-ui/index.html

To run the repository - 

From the repository root, 

1. run `./gradlew bootRun`run the the project on port 8081.
2. run `./gradlew bootJar` to create executable jar. The jar will be located inside build directories.
