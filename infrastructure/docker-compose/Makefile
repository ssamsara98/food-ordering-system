zookeeper-up:
	docker-compose -f ./common.yml -f ./zookeeper.yml up $(arg)
zookeeper-down:
	docker-compose -f ./common.yml -f ./zookeeper.yml down $(arg)

kafka-cluster-up:
	docker-compose -f ./common.yml -f ./kafka_cluster.yml up $(arg)
kafka-cluster-down:
	docker-compose -f ./common.yml -f ./kafka_cluster.yml down $(arg)

init-kafka-up:
	docker-compose -f ./common.yml -f ./init_kafka.yml up $(arg)
init-kafka-down:
	docker-compose -f ./common.yml -f ./init_kafka.yml down $(arg)

dc-down:
	docker-compose -f ./common.yml -f ./init_kafka.yml -f ./kafka_cluster.yml -f ./zookeeper.yml down $(arg)
