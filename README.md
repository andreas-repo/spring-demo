### Start demo database
1.) docker image pull postgres/latest

2.) docker run --name springDemoDB -p 5432:5432 -e POSTGRES_USER=demo -e POSTGRES_PASSWORD=demo -e POSTGRES_DB=demoDB -d postgres


### References for used technology
#### OAuth2.0
https://spring.io/guides/tutorials/spring-boot-oauth2/

#### Serving Web Content
https://spring.io/guides/gs/serving-web-content/

#### Simple security 
https://spring.io/guides/gs/securing-web/