###Q/A session

####Service Discovery Patterns (slide 10)

client-side discovery
- list of services available on client (either local config or server side registry) 
- client implements load balancing and failover

server-side discovery
- list of services available on dedicated load balancer
- load balancer routes client requests accordingly
- client just implements retry (circuit breaker) logic

in both cases an automated provisioning approach (self registration or via external registrar) as well as periodic health checks are necessary to keep list of healthy services up-to-date!
