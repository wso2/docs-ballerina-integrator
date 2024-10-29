# Entrypoint

Ballerina Integrator provides a set of built-in entry points to expose services. These entry points are used to expose services to the outside world. 
The following section describes the entry points supported in Ballerina Integrator and how to create them.

## Services
Following service types are supported in Ballerina Integrator:
    
### HTTP Service
HTTP service is a network-accessible API that is defined by a set of resources and methods. 
To start your integration with an HTTP service, click on the `HTTP Service` Button in the `Service Type` section.
HTTP service can be designed using Service Designer or by importing an OpenAPI Specification (OAS) file to set it up quickly.

1. Design From Scratch 
    - Select the `Design From Scratch` option.
    - Enter the service name as `HelloWorldService`, path as `/hello` and `9090` as the port.
    - Click on the `Create Service` button.
    - This will create a new service with the name `HelloWorldService` and the path `/hello` on port `9090`.
    - You can now design the service by adding resources and methods to it.

2. Import OpenAPI Specification
    - Select the `Import OpenAPI Specification` option.
    - Click on the `Choose File` button and select the OAS file.
    - Click on the `Create Service` button.
    - This will create a new service with the details specified in the OAS file.
    - You can now design the service by editing resources and methods to it.

 
### GraphQL Service

## Tasks

## Triggers
