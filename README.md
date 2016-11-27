# Hello World

Basic Example for Using Dropwizard

usage:
In the project directory run:
java -jar target/hello-world-0.1.0-SNAPSHOT.jar server hello-world.yml

Examples of requests and responses:

Request URL: http://localhost:8080/hello-world

Response: {"id":1,"content":"Hello, Stranger!"}


Request URL:http://localhost:8080/hello-world?name=Successful+Dropwizard+User

{"id":2,"content":"Hello, Successful Dropwizard User!"}


