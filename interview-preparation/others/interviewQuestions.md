
# Other Interview Questions

## 1. How to Implement Security in an Application

- **Authentication**: user identity system <JWT, OAuth2, or OIDC>
- **Authorization**: check permissions/previleges on every API call
- **Encryption**: HTTPS / TLS everywhere
- **Input Validation**:
- **Secrets Management**:
- **Session & Token Security**:
- **Logging: Never log passwords or tokens
- **Dependency Security**: Run `govulncheck` to check known vulns
- **Rate Limiting : Prevent brute-force and abuse
- **Kubernetes / Cloud** : RBAC, Network Policies
- **Monitoring & Alerts**: Set up monitoring for failed logins, spikes, or suspicious requests
- **CI/CD & Deployment**: code scanning tools


# EPAM INTERVIEW QUESTIONS 

- L1 Technical Round: 

## What are the main differences between threads in Python and Goroutines in Go?
## Why do we use threads in Python or Goroutines in Go?
## What are the advantages of SQL databases over NoSQL databases?
## What is the purpose of ACID properties, and when do we need to consider them?
## Have you heard about BASE properties in databases?
## What is the CAP theorem?
## How do you update the status to 'inactive' for users with age greater than 50 in a user table?
## How would you update the status to 'inactive' for users with age greater than 50 in a NoSQL database?
## What is the difference between "update" and "set" in NoSQL databases?
## How do you fetch the fifth highest salary from an employee table in SQL?
## What is the purpose of indexes in databases?
## What different types of web communication protocols do you have experience with?
## What are the advantages of gRPC over HTTP/REST?
## What different security measures would you use to secure an API?
## How do you check code coverage for your Go unit tests?


## Coding Task: How do you implement a rate limiter in Go to allow only 10 requests per second, returning an error for the 11th request, without using third-party libraries? How would you implement client-specific rate limiting in Go, where each client can have a different request limit per second?
## Coding Task: Implement OOPs
## Coding Task: How would you design a Go program to efficiently find and print composite numbers in a large range using concurrent goroutines, with a worker pool, channels, context for cancellation, and ordered output?

- L2 Project Fitment: 

## Question: What are your first steps and main considerations when building a microservice end-to-end from scratch?
## Question: What do you usually declare in a protobuf file, and what does it typically look like?
## How would you declare endpoints for a todo microservice in a protobuf file?
## How would you add pagination and filtering to the ListTodos endpoint in a todo microservice's protobuf definition?
## Is the order of fields in protobuf messages important for a gRPC microservice, and how does it affect future development?
## How do you usually document your gRPC API and provide it to customers?
## How can you expose gRPC microservice endpoints externally as REST APIs?
## Can a gRPC reverse proxy (like grpc-gateway) be generated automatically from the protobuf file?
## What types of gRPC streaming are there?
## How do you handle connection loss or long response times in gRPC bidirectional streaming between on-prem and cloud components? What patterns are used to maintain or re-establish the connection?
## What steps do you usually take to add database support to a microservice?
## How do you smoothly support initial table creation and later schema changes (like altering tables) in a microservice using PostgreSQL?
##  What needs to be declared to deploy a microservice in a Kubernetes cluster?
## Which tool do you usually use to declare Kubernetes resources for your microservice projects?
## Besides Helm, what other tools or methods can be used to manage Kubernetes resources?
## How do you get the list of running services in a Kubernetes cluster?
## Do you know about Custom Resource Definitions (CRDs) in Kubernetes?
## Do you know anything about Dapr?
## What entities do you usually create in a microservice to support Kafka integration?
## How is the database structure mapped to internal entities in a microservice, and how is this mapping supported for making SQL calls to PostgreSQL?
## Why do we need multi-stage builds in a Dockerfile?
## Does using multi-stage builds make the final Docker image smaller or larger?
## Do you use Makefile or make tools when building microservices, and are you familiar with them?
## How would you implement a ping pong game in Go using channels and goroutines, where two players serve the ball back and forth for 2 minutes, waiting a random time (0–10 seconds) before serving, and the player holding the ball at the end wins?
## Do you know anything about context in Go?

## Coding Task: The task is to implement a ping pong game in Go using channels and goroutines, where two players serve the ball back and forth for 2 minutes, waiting a random time (0–10 seconds) before serving, and the player holding the ball at the end wins.

