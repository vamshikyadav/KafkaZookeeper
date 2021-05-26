# KafkaZookeeper
KafkaZookeeper -> deployment on GKE

# Zookeeper files are used for Zookeeper deployment

zoo-deployment.yaml
zoo-service.yaml

# Kafka files are used to deploy Kafkabrokers

kafka-service.yaml
kafkabroker-deployment.yaml

# Images Used:
kafka: wurstmeister/kafka
ZooKeeper: zookeeper:latest

# Config: 
KAFKA_ADVERTISED_HOST_NAME : <loadbalancerendpoint>