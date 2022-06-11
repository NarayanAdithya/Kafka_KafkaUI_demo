# Setting Up Kafka with Kafka UI
The following is a simple way to setup Kafka brokers using `docker-compose` along with KafkaDrop UI.

### Setup Instructions
1. Clone the repo using `https://github.com/NarayanAdithya/Kafka_KafkaUI_demo.git`
2. Set the terminal directory into the `Kafka_KafkaUI_demo` folder
3. Run `docker-compose up`
4. Once the setup is complete check `localhost:9000` for the KafkaDrop Interface
5. You have successfully setup Kafka with KafkaDrop

### Setup Instructions for Python
1. Run `pip install -r requirements.txt`, this will install the necessary packages required
2. Run `python kafka_producer.py`, this will produce data to the kafka broker.
3. In a different terminal or same run `python kafka_consumer.py`, we can see that the data that was pushed was read successfully from the broker.
4. Press `ctrl+c/z` to exit the consumer script which keeps listening for new messages produced.
