# System_Design

## System Design 
It's a process of planning how different parts of a large project, like a website or app, will work together to solve a problem efficiently and reliably. It's like creating a blueprint for how all the pieces will fit and function smoothly.
- **Scope**: High-level design that covers the whole system.
- **Focus**: Solving a problem by considering scalability, performance, and reliability.
- **Example**: 
  - Designing an online shopping system.
  - Deciding how users, product catalog, shopping cart, and payment services interact.

### Key Considerations:
- **Components**: Identify all key parts (e.g., front-end, back-end, database).
- **Data Flow**: How data moves between components (e.g., API calls).
- **Non-Functional Requirements**: Performance, security, scalability.


## Architecture
It refers to the high-level structure of a system. It defines how different components (like databases, servers, clients, etc.) are organized and how they interact with each other. Think of it as the blueprint for a house, showing the big picture of how rooms (components) are connected and how people (data) move between them.
- **Scope**: Structural and organizational blueprint of the system.
- **Focus**: Deciding how to organize the components, and ensuring the system is modular, scalable, and maintainable.
- **Example**:
  - Choosing **Microservices Architecture** for the online shopping system so that each service (e.g., product, payment, shipping) is independent and scalable.

### Common Types of Architectures:
- **Monolithic Architecture**: All components in a single codebase.
- **Microservices Architecture**: Components are independent services.
- **Layered Architecture**: Organized into layers (presentation, business logic, data).


## Design Pattern
It is a reusable solution to a common problem that occurs in software design. It’s like a best practice or a template that helps solve specific design issues. While architecture is about the overall structure, design patterns focus on how individual components or modules inside the system solve recurring problems.
- **Scope**: Solutions for common problems at the code level.
- **Focus**: Optimizing code structure and behavior within the system.
- **Example**:
  - Using the **Observer Pattern** in the shopping system to notify users when their order status changes.
  - Using the **Factory Pattern** to manage different payment gateways (PayPal, Credit Card, etc.).

### Common Design Patterns:
- **Creational Patterns**: Solve object creation problems (e.g., Singleton, Factory).
- **Structural Patterns**: Solve class and object composition (e.g., Adapter, Decorator).
- **Behavioral Patterns**: Manage object interactions (e.g., Observer, Strategy).

## Summary of Differences:

| Aspect               | System Design                      | Architecture                         | Design Patterns                          |
|----------------------|------------------------------------|--------------------------------------|------------------------------------------|
| **Definition**        | Overall planning of how the system works | High-level structural blueprint       | Reusable solutions to specific design problems |
| **Scope**             | Big picture – entire system        | Structure and organization of components | Code-level problem-solving in components |
| **Focus**             | Problem-solving and requirements   | Organizing components for scalability, performance | Optimizing code structure and behavior  |
| **Example**           | Designing an online store          | Choosing Microservices for modularity | Using Observer Pattern for notifications |

## Example in IT Industry

### System Design:
- In designing a **real-time messaging app** like WhatsApp, you’d consider how the app will handle millions of users, send/receive messages instantly, and handle failures.
  
### Architecture:
- You may decide to use **Event-Driven Architecture** so that all messages are sent asynchronously using a message broker (e.g., Kafka), allowing better scalability and fault tolerance.

### Design Patterns:
- You could implement the **Observer Pattern** to notify users in real time when they receive a new message. Additionally, use the **Factory Pattern** to manage different types of messages (text, image, video).
