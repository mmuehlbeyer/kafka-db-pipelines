FROM confluentinc/cp-server-connect-base:7.5.1
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-datagen:0.5.2
RUN confluent-hub install --no-prompt debezium/debezium-connector-postgresql:2.2.1
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.7.0
RUN confluent-hub install --no-prompt debezium/debezium-connector-postgresql:2.2.1