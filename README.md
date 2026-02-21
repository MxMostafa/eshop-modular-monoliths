# eshop-modular-monoliths
Project Name: Enterprise E-Commerce Platform (Modular Monolith)

Description:
Designed and developed a highly scalable e-commerce backend using .NET 8 and Modular Monolith Architecture. Unlike traditional monoliths, this solution implements Clean Architecture and Domain-Driven Design (DDD) to ensure low coupling and high cohesion between modules (Catalog, Ordering, Basket).

Tech Stack & Key Features:

Architecture: Implemented CQRS pattern using MediatR to separate read and write operations.
Data: Utilized PostgreSQL for transactional data and Redis for high-performance session/basket management.
Communication: Integrated MassTransit with RabbitMQ for asynchronous inter-module communication (e.g., OrderCreated -> Inventory check).
Security: Secured APIs using JWT and IdentityServer.
Testing: Achieved high code coverage using xUnit and Moq.
DevOps: Containerized the entire solution using Docker and Docker Compose for local development.
Frontend: Built a responsive admin dashboard with Angular 18 and Reactive Forms.
Why this stack helps you get hired:
Modular Monolith: Shows you understand the trend of avoiding premature Microservices.
CQRS & MediatR: Shows you write maintainable, scalable code.
Redis & RabbitMQ: Shows you understand distributed system concepts, even within a monolith.
Docker: Shows you understand deployment.
