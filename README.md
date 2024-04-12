#  Most commonly used function in js (Cheat!)

* **1-Destructuring**
* **2-Rest Spread Operator {},[]**
* **3-Template Literals**
* **4-Ternaries Instead of ifelse Statements**
* **5-Arrow Functions**
* **6-ShortCircuiting And Logical Operators && ||**
* **7-nullish operator**
* **8-Optional Chaining**
* **9-The Array map Method**
* **10-The Array filter Method**
* **11-The Array reduce Method**
* **12-The Array sort Method**
* **13-Working With Immutable Arrays**
* **14-Asynchronous JavaScript Promises**
* **15-Asynchronous JavaScript AsyncAwait**
## Features

* **Catalog microservice which includes** : 

    - ASP.NET Core Web API application
    - REST API principles, CRUD operations
    - MongoDB database connection and containerization
    - Repository Pattern Implementation
    - Swagger Open API implementation

* **Basket microservice which includes** : 

    
    - ASP.NET Web API application
    - REST API principles, CRUD operations
    - Redis database connection and containerization
    - Consume Discount Grpc Service for inter-service sync communication to calculate product final price
    - Publish BasketCheckout Queue with using MassTransit and RabbitMQ

* **Microservices Communication** :
    - ASP.NET Grpc Server application
    - Build a Highly Performant inter-service gRPC Communication with Basket Microservice
    - Exposing Grpc Services with creating Protobuf messages
    - Using Dapper for micro-orm implementation to simplify data access and ensure high performance
    - PostgreSQL database connection and containerization

* **Discount microservice which includes** :

    - Sync inter-service gRPC Communication
    - Async Microservices Communication with RabbitMQ Message-Broker Service
    - Using RabbitMQ Publish/Subscribe Topic Exchange Model
    - Using MassTransit for abstraction over RabbitMQ Message-Broker system
    - Publishing BasketCheckout event queue from Basket microservices and Subscribing this event from Ordering microservices
    - Create RabbitMQ EventBus.Messages library and add references Microservices

* **Ordering Microservice** :
    - Implementing DDD, CQRS, and Clean Architecture with using Best Practices
    - Developing CQRS with using MediatR, FluentValidation and AutoMapper packages
    - Consuming RabbitMQ BasketCheckout event queue with using MassTransit-RabbitMQ Configuration
    - SqlServer database connection and containerization
    - Using Entity Framework Core ORM and auto migrate to SqlServer when application startup
* **API Gateway Ocelot Microservice**

    - Implement API Gateways with Ocelot
    - Sample microservices/containers to reroute through the API Gateways
    - Run multiple different API Gateway/BFF container types
    - The Gateway aggregation pattern in Shopping.Aggregator

* **WebUI ShoppingApp Microservice**

    - ASP.NET Core Web Application with Bootstrap 4 and Razor template
    - Call Ocelot APIs with HttpClientFactory and Polly

* **Ancillary Containers**:

    - Use Portainer for Container lightweight management UI which allows you to easily manage your different Docker environments
    - pgAdmin PostgreSQL Tools feature rich Open Source administration and development platform for PostgreSQL

* **Docker Compose establishment with all microservices on docker**:

    - Containerization of microservices
    - Containerization of databases
    - Override Environment variables



   

    

## Contributions and Support

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

If you encounter any issues or have questions about using the UI, please check the existing issues in the repository. If your problem persists, feel free to open a new issue, and the community will be happy to assist you.
## Acknowledgements


We would like to thank the contributors and the open-source community for their valuable contributions and support, making this project possible.

If you find this project helpful or have any suggestions, we would love to hear from you!

Happy coding!


## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the codebase as per the terms of this license.
