## 2016

[Reactive Summit 2016](https://www.reactivesummit.org)

# Title:
Implementing an akka-streams materializer for big data

# Abstract:
Akka Streams provides a tremendously flexible architecture to build reactive pipelines that can be imported, exported and otherwise composed as partial DAGs. Its current, default implementation is ActorMaterializer which provides reactive streams across actors within a single JVM. 
Here we show how we implemented a GearpumpMaterializer which distributes reactive streams across a set of remote workerson the Apache Gearpump platform. We discuss how this was implemented and a number of challenges we faced with specific GraphStages and their semantics. Additional we cover how different materializer implementations can interoperate together to materialize different parts of the pipeline. We show that the changes we introduced internally within Akka Streams will enable other implementations of akka stream materializers and suggest a template based on our implementation. We will contribute the Gearpump materializer as open source to https://github.com/akka/akka-stream-contrib or make it available as part of an upcoming Apache Gearpump release.

[Software Architecture Conference April 3-5, New York, NY](http://conferences.oreilly.com/software-architecture/sa-ny/public/cfp/493)
