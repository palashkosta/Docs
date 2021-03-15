### Services Alternatives

| Service | Usage | AWS | Google Cloud | M Azure | Other |
| ------- | ----- | --- | ------------ | ------- | ----- |
| Zipkin | Distributed Tracing | AWS X-Ray | | | Splunk |
| Eureka Naming Server | Solve the problem of service discovery for microservices | ECS (automatically) | | | Hashicorp Consul |
| Spring Cloud Gateway | | | | | |


### Cross-Service Challenges
https://docs.aws.amazon.com/whitepapers/latest/microservices-on-aws/microservices-on-aws.html
- Service discovery
  - Amazon ECS now includes integrated service discovery that makes it easy for your containerized services to discover and connect with each other. 
  - Amazon ECS creates and manages a registry of service names using the Route 53 Auto Naming API.
  - A different approach to implementing service discovery is using third-party software like HashiCorp Consul, etcd, or Netflix Eureka.
- Data consistency
- Asynchronous communication
- Distributed monitoring and Auditing
