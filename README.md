# ACI Rental system

This project is in development for the ACI Fontys studies. The project is created to make ACI's own rental system.
Currently ACI uses a system, used Fontys wide, to loan items (i.e video cameras, lenses, lighting) to student. The Fontys system has a lot of functionality that goes unsused within the usage of the ACI context and some of the features are not optimal for ACI. This project uses some of the old functionality mixed with new functionality to create a new ACI rental system.

## Code
The project uses a microservice architecture. This is to scale the code and keep the difference services autonomous. The microservice architecture has a monorepo for all services, the main purpose for this is the CI/CD and easy development. 

### Language & Frameworks
- .NET Core 5.0
- Entity Framework
- AngularJS - HTML, SCSS, Typescript, Javascript
- Cypress
- Github Actions
- Microk8s

### Repositories
- [Backend](https://github.com/ACI-Rental/backend)
- [Frontend](https://github.com/ACI-Rental/front-end)
- [Docs](https://github.com/ACI-Rental/docs)

### Architectural Styles
* Microservices
* Event streaming

### Deployment
* Docker
* DockerHub
* Microk8s
* Ubuntu 20.04

## Docs
The docs contain information regarding the project and files used. The docs contain the following type of documents:
- Handover document - contains choices made, how to setup and use 3Rd party tools used and code conventions.
- Kubernetes files used for deployment
- Architectural documents
- Github action example yammels

## Contributing and getting started
Please refer to the [CONTRIBUTING.md](https://github.com/ACI-Rental/docs/blob/main/CONTRIBUTING.md) file for more information
