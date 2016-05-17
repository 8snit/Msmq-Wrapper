# Operations Ready Microservices

Decomposing a monolith into many microservices inherently complicates operations based on the increased number of deployed components to manage and keep track of. Entering the realm of distributed systems also requires fault-tolerant, self-healing solutions to overcome the fallacies of distributed computing. Components are expected to come and go and to change their location, resulting in a highly dynamic IT system landscape. As failures will happen more frequently, tracking the message flow between the individual components is crucial. This talk introduces several boilerplate patterns that help to tackle these challenges and demonstrates how an operations model for microservices can be implemented with open source components of the Netflix OSS and Spring Cloud stack.

Note: this talk has not been accepted yet!

### Topics

- service registration & discovery 
- load balancing
- dynamic routing
- circuit breaker
- configuration management
- health monitoring & metrics
- log correlation & tracing
- security
