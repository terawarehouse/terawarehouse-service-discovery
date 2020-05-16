[![patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/bePatron?u=12280211)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Catalog Module

Is a microservice that is a part of the Catalog and Sellout Management System.

## Features

 - It is powered by Spring Cloud that provides the microservice registry server functionality.
 - It is using Eureka as the client server discovery.

## Dockerized

```
docker build -t com.terawarehouse/service-discovery-server .
docker run -d -p 8761:8761 com.terawarehouse/service-discovery-server
```

Service discovery should be accessible at For example: http://192.168.1.101:8761

## Repositories

 - https://github.com/terawarehouse
 
## Authors

 * **Edward P. Legaspi** - *Java Architect* - [czetsuya](https://github.com/czetsuya)
