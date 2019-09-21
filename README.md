# Azure Spring Cloud training

You will find here a full workshop on Azure Spring Cloud, including guides and demos.

This is done by [Julien Dubois](https://twitter.com/juliendubois) and available for free to everyone, under the [Apache 2 license](LICENSE.txt).

## What you should expect

This is not the official documentation, but an opinionated training.

It is made to by hands-on, and will use the command line extensively. The idea is to get coding very quickly and play with the platform, from a simple demo to far more complex examples.

After completing all the guides, you should have a fairly good understanding of everything that Azure Spring Cloud offers.

## Prerequisites

- Java 11 or above
- The [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli/?WT.mc_id=azurespringcloud-github-judubois)

## [01 - Create a cluster](01-create-a-cluster/README.md)

Basics on creating a cluster and configuring the CLI to work efficiently.

## [02 - Build a simple Spring Boot microservice](02-build-a-simple-spring-boot-microservice/README.md)

Build the simplest possible Spring Boot microservice, made with [https://start.spring.io/](https://start.spring.io/).

## [03 - Debug and monitor applications on Azure Spring Cloud](03-debug-and-monitor-applications-on-azure-spring-cloud/README.md)

Access Spring Boot applications logs and metrics to understand common issues.

## [04 - Configure a Spring Cloud Config server](04-configure-a-spring-cloud-config-server/README.md)

Configure a [Spring Cloud Config Server](https://cloud.spring.io/spring-cloud-config), that will be entirely managed and supported by Azure Spring Cloud, to be used by Spring Boot microservices.

## [05 - Build a Spring Boot microservice using Spring Cloud features](05-build-a-spring-boot-microservice-using-spring-cloud-features/README.md)

Build a Spring Boot microservice that is cloud-enabled: it uses a discovery server ([Eureka](https://github.com/Netflix/eureka)) and a [Spring Cloud Config Server](https://cloud.spring.io/spring-cloud-config) which are both managed and supported by Azure Spring Cloud.

## [06 - Build a reactive Spring Boot microservice using CosmosDB](06-build-a-reactive-spring-boot-microservice-using-cosmosdb/README.md)

Build a reactive Spring Boot microservice, that uses the [Spring reactive stack](https://docs.spring.io/spring/docs/current/spring-framework-reference/web-reactive.html) and is binded to a [CosmosDB database](https://docs.microsoft.com/en-us/azure/cosmos-db/?WT.mc_id=azurespringcloud-github-judubois) in order to access a globally-distributed database without optimum performance.

## [07 - Build a Spring Boot microservice using MySQL](07-build-a-spring-boot-microservice-using-mysql/README.md)

Build a classical Spring Boot application that uses JPA to acess a [MySQL database managed by Azure](https://docs.microsoft.com/en-us/azure/mysql/?WT.mc_id=azurespringcloud-github-judubois).

## 08 - Build a Spring Boot gateway

TO BE DEFINED

## [09 - Putting it all together, a complete microservice stack](09-putting-it-all-together-a-complete-microservice-stack/README.md)

Run several microservices together and expose them with a gateway, in order to have a full microservices stack running. Will we use Azure Cloud Service's distributing tracing mechanism to better understand this system.