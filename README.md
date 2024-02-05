# food-ordering-system
Microservices: Clean Architecture, DDD, SAGA, Outbox &amp; Kafka

- install [graphviz](https://graphviz.org/download)
- check [depgraph-maven-plugin](https://github.com/ferstl/depgraph-maven-plugin) documentation
- run
  - `mvn com.github.ferstl:depgraph-maven-plugin:graph`
  - `mvn com.github.ferstl:depgraph-maven-plugin:aggregate -DcreateImage=true -DreduceEdges=false -Dscope=compile "-Dincludes=com.food.ordering.system*:*"`