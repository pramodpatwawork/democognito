# democognito

## cognito poc

* https://rieckpil.de/thymeleaf-oauth2-login-with-spring-security-and-aws-cognito/
* https://arjunsk.medium.com/resource-server-with-cognito-b7fbfbee0155
* https://medium.com/swlh/authenticate-spring-boot-api-with-aws-cognito-cbb6f4d7a10a
* https://blog.devgenius.io/example-of-spring-boot-application-authentication-with-aws-cognito-55ce34fa53dc

## Google APP setting

* Go on google developer console.
* Create new project
* Go on credential
* configure auth consent screen
* Create new Credential
* Authorized JavaScript origins > URIs > https://{cognito_domain_name}.auth.eu-west-1.amazoncognito.com
* Authorized redirect URIs > Uris > https://{cognito_domain_name}.auth.eu-west-1.amazoncognito.com/oauth2/idpresponse
* click on create and copy client id and secret and register in provider section of congnito.
