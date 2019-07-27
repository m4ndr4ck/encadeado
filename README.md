# encadeado

Encadeado is a software that automates the bootstrap proccess of new applications in an enterprise environment. By providing just the application name it will handle all the necessary processes to create:

- CI/CD pipelines with Jenkins
- Git and Nexus repositories
- Application skeleton code based on software architecture templates
- Databases
- Logging mechanism sending data to ELK
- Prometheus ServiceMonitors 
- Kubernetes deployments of the first bootstrapped version on predefined environments

The end result will be an application ready to start its development lifecycle with all proper things in place.
Encadeado stongly relies on microservice and DevOps principles.
