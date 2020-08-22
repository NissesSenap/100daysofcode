# 100 days of code

Stolen lots of things from: [https://www.100daysofcode.com/](https://www.100daysofcode.com/)

I will try to make a 100 days of code project.
But I don't plan to make a bunch of small 30 lines of code stuff.

Instead I want to create a bigger project that contains a bunch of features that I want to learn more about.
This app wont "do" anything useful, just store some small messages and send them back and forth.

If i manage to do something useful with this project I will most likely create it as a separate project since this will lots of random commits.

My plan is to use go and kubernetes to deploy these applications.

## What to do

My plan is to create a project that can be used to verify functionality of a Kubernetes cluster.

What the app should contain

- GRPC with protobuf
- REST API using grpc-gateway
- Message bus like kafka and nats
- External database like postgres and maybe something like etcd
- OpenTelemetry for tracing & metrics
- Graceful shutdown on interrupt signals
- Manage the different enabled services through feature flags or config
- Health checks
- Unit tests

## Links and ideas

Here is a great example repo that I will probably steel a bunch of stuff from [podinfo](https://github.com/stefanprodan/podinfo)

### Design

Lets try this Hexagonal design thing :)

[Building Hexagonal Microservices with Go - Part One](https://www.youtube.com/watch?v=rQnTtQZGpg8)

[Building Microservices with the Go Kit Toolkit](https://www.youtube.com/watch?v=sjd2ePF3CuQ)

### gRPC

[Building and Basic API with gRPC and Protofbuf](https://www.youtube.com/watch?v=Y92WWaZJl24)
