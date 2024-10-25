# test-ai

I wrote to copilot "What files will I need for a basic spring project?".
It responded with

```
pom.xml (for Maven projects) or build.gradle (for Gradle projects) - This file manages project dependencies.
Application.java - The main class to bootstrap the Spring application.
application.properties or application.yml - Configuration file for Spring Boot.
Controller class - To handle HTTP requests.
Service class - To contain business logic.
Repository interface - For data access layer (if using Spring Data JPA).
Entity class - To map to database tables (if using Spring Data JPA).

Pseudocode for setting up a basic Spring Boot project:
Create a new Maven or Gradle project.
Add Spring Boot dependencies in pom.xml or build.gradle.
Create the main application class with @SpringBootApplication annotation.
Create a Controller class with @RestController annotation.
Create a Service class with @Service annotation.
Create a Repository interface with @Repository annotation (if using Spring Data JPA).
Create an Entity class with @Entity annotation (if using Spring Data JPA).
Configure application properties in application.properties or application.yml
```

It made me a pom.xml file, so I asked it to make a build.gradle one instead, which I copy pasted.

I then asked where to put the appliction.properties it gave me and it gave me the file structure I made.
I pasted the code given, but had to fix the package path.
In the end it couldn't make a working version of Application.java without human intervention.
