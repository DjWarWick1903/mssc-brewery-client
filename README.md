# SFG Beer Works - Brewery Client

Source code in this repository is to support my on line courses:
* [Spring Boot Microservices with Spring Cloud](https://www.udemy.com/spring-boot-microservices-with-spring-cloud-beginner-to-guru/?couponCode=GIT_HUB2)

Assignment 1:
* Create client using Spring RestTemplate for Customer API operations
* Follow Beer API client as example, write tests for each method
* Complete the following:
  * GET
  * POST
  * PUT
  * DELETE

Assignment 2:
* Hard coding configuration values is generally considered a bad practice
* HTTP client properties are currently hard coded
* These often need to be changed in deployments for performance tuning
* Externalizing will alow the configuration values to be changed without rebuilding
* Assignment - Use Spring to externalize properties of BlockingRestTemplateCustomizer
  * Externalize connection and timeout values