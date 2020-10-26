# Marlabs
a Marlabs web application project based on REST API secured by using JWT (JSON Web Token) with Spring Security and Spring Boot.

# Codes Description 
There are total four packages in this project:
- config
- controller
- model
- service

## config
In the config package, there are four java files for JWT configuration:
- JwtAuthenticationEntryPoint.java
- JwtRequestFilter.java
- JwtTokenUtil.java
- WebSecurityConfig.java

## controller
In the controller package, there are two java files:
- JwtController.java
- JwtAuthenticationController.java

All endpoints for CRUD operations can be seen in java files above.

## model
- JwtRequest.java

JwtRequest.java contains username and password as a request.

- JwtResponse.java

JwtResponse.java returns the response containing JWT token.

## service
- JwtUserDetailsService.java

This java file is aimed to display details of JWT token.
