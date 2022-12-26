## Exposing health end-point for Micronaut App.

<!-- wp:paragraph -->
<p>In this Repo we have exposed a health endoint for micronaut Application. </p>
<!-- /wp:paragraph -->

- Creatd Flight web app


## Requirements
- Micronaut
- Gradle 3.6.1 
- JDK 1.8 or greater installed with JAVA_HOME
- Enable annotation Processing.
  - ![1 5](https://user-images.githubusercontent.com/85616604/196144615-83ca2d81-667f-4832-9783-9575cee4dce6.png)

## How to run the project?

- Test the Application.
  - ./mvnw test

- Run the Main App : 
   ![Screenshot from 2022-12-26 19-46-30](https://user-images.githubusercontent.com/85616604/209557762-c8e22e42-39a7-464c-ba71-50570b22f94c.png)
 
- curl localhost:8080/health 
   ![Screenshot from 2022-12-26 19-46-02](https://user-images.githubusercontent.com/85616604/209557827-3c96e2c8-5392-4b39-9953-6f4550e28016.png)





