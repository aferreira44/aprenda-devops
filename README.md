# aprenda-devops-microservices

## Glossary

* Feedback Loop
* DevOps
* Equal environments (Dev / Staging / Prod)
* Microservices
* Technical debt
* DDD - Domain-Driven Design
* Deployment Pipeline
* Zero Downtime
* Proxies and Load Balancers (haproxy and nginx)
* Blue-Green Deployment
* Canary Deployment
* Smart Routers
* Feature-Toogle
* A/B Testing
* Application State - Ephemeral x Persistent  (Redis, Infinispan, Memcached)

## Tips

* A very mature software deployment pipeline is an absolute requirement for any microservices architeture
* Indicators of a good pipeline maturity:
  * Amount of manual intervention required
  * Amount of automated tests
  * Automatic provisioning of environments
  * Monitoring
  
* Problems to take care on distributed systems: Tracing, monitoring, log aggreagation, resiience
* Improve our lead time and reducing the batch size of our releases
* Each microservice should have its own separate database
* Strangler Pattern: start with a monolith and a relational database and break up to microservices and different DBs later

## Resources

* Book: Migrating to Microservice Databases - Edson Yanaga
