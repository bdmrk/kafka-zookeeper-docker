-- Start Kafka Zookeeper Server (service registry)
-- Start Kafka Broker Server
-- Create Kafka Topic
-- Create Spring Boot Project with Kafka Configuration
-- Publish Message to Topic from Sprint Boot App
-- kafka clustering
-----------------------facility------------------
1. write 2 million data per seceond
2. logg aggregator
3. event sourcing for micro services
4. zero downtime

---------------------------------------------------------------------
kafka command after docker up 

1. docker exec -it kafka bin/sh // docker execute in interactive kakafa shell mode
2. ls
3. cd /opt/
4. ls
5. cd kafka
6. ls
7. cd bin/
8. ls
9. cd ..
10. create topic run the command

./bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic kausar

11. kafka list---
./bin/kafka-topics.sh --list --zookeeper zookeeper:2181

