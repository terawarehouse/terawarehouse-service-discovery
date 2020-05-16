[![patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/bePatron?u=12280211)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Catalog Module

Is a microservice that is a part of the Catalog and Sellout Management System.

## Features

 - It is powered by Spring Cloud that provides the microservice registry server functionality.
 - It is using Eureka as the client server discovery.
 
## Application Configuration

To use either configuration instance1 or intance2 in src/main/resources folder set the value of spring.profiles.active in your environment variable. 
For instance if we will be using instance1 then spring.profiles.active=instance1.

## Dockerized

```
docker build -t czetsuya/terawarehouse-service-discovery .
docker run -d -p 8761:8761 czetsuya/terawarehouse-service-discovery
```

Service discovery should be accessible at For example: http://localhost:8761

## Repositories

 - https://github.com/terawarehouse
 
## Authors

 * **Edward P. Legaspi** - *Java Architect* - [czetsuya](https://github.com/czetsuya)
