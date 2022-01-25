# rabbit-todo

[![Git](https://app.soluble.cloud/api/v1/public/badges/6f6a359b-b987-4081-a01f-5a8dee73f031.svg?orgId=521549019486)](https://app.soluble.cloud/repos/details/github.com/brianbyers/rabbit-todo?orgId=521549019486)  

SEE THE POST FOR DETAILS: [http://rabbitstack.github.io/spring-mvc-angular-hasta-la-vista-jsp/](http://rabbitstack.github.io/spring-mvc-angular-hasta-la-vista-jsp)

A simple collaborative real time application with Angular and Spring MVC. The purpose of this application is to showcase the integration between Angular / Spring MVC using MongoDB as backing store and websockets for the interactivity.

### Requirements

*   JDK 8
*   MongoDB
*   Gradle
*   Bower
*   Compass (optional)

### Setup
Install the required dependencies. Clone the repository. Go to the main directory and run `bower install` to setup JS dependencies. Next, run `gradle assemble` to configure the jar artifacts. Run the embedded Jetty container with `gradle appRun` and go to `http://localhost:8080/rabbit-todo`.
