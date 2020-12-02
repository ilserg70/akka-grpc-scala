# akka-grpc-scala
Example of gRPC service/client on Scala with Akka

### Run service

```
./sbt compile
./sbt "runMain com.example.helloworld.GreeterServer"
```

### Run client

```
./sbt "runMain com.example.helloworld.GreeterClient"
```