# dropwizard-hello-world
A hello world app run on a server supported by Dropwizard

It is a useful backend tool that helps developers create a RESTful web application.

To run the server:
1. In the project directory, run the following
java -jar target/HelloWorldApplication-0.0.1-SNAPSHOT.jar server hello-world.yml
2. Now the application is listening on ports 8080 for application requests and 8081 for administration requests.

To check whether the configuration is ok, run the following: 
java -jar target/HelloWorldApplication-0.0.1-SNAPSHOT.jar check hello-world.yml


Reference: http://www.dropwizard.io/0.9.1/docs/getting-started.html