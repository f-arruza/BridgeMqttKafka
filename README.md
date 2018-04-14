# BridgeMqttKafka - Grupo1

Componente que garantiza la comunicación entre los servidores de mensajería Mosquitto y Apache Kafka.

Para ejecutarlo se debe utilizar el comando:

java -jar mqttKafkaBridge-0.1.0.jar --id taller03 --uri tcp://172.24.41.178:8083 --zk 172.24.41.178:8088 --kfk 172.24.41.178:8089 --topics '#'
