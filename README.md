# springboot-kafka-microservice
Project for learning springboot-kafka-microservice

## Kafka Setup
```
$ tar -xzf kafka_2.13-3.4.0.tgz
$ cd kafka_2.13-3.4.0
```
NOTE: Your local environment must have Java 8+ installed.

Apache Kafka can be started using ZooKeeper.

## Kafka with ZooKeeper
Run the following commands in order to start all services in the correct order:

#### Start the ZooKeeper service
```
$ bin/zookeeper-server-start.sh config/zookeeper.properties
```
Open another terminal session and run:

#### Start the Kafka broker service
```
$ bin/kafka-server-start.sh config/server.properties
```
Once all services have successfully launched, you will have a basic Kafka environment running and ready to use.
