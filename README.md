# PropelleraeroInfraChallenge
Docker example with NginX + Auth-Request module proxying to auth-acting Monolithic server for Microservice app
This is a Docker setup for a Monolithic application acting as an authentication and authorization server for a Microservice application, through the NginX reverse-proxy and auth-request module.

1. We use NginX as reverse proxy.
2. We use auth-request module to add an authorization step for each request directed to Microservice.
3. The initial Micorservice application main page is wrapped into a Monolithic-powered page, so we can build an interface above Microservice, with user and access rights management.
