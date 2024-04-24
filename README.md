a. How many data your publlsher program will send to the message broker in one run?

According to main in main.rs, the publisher program will send 5 messages in one run. It can be seen from the amount of publish_event method call in the main function.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

It means both subscriber and publisher are connecting to the same AMPQ broker. The publisher publishes to the same broker as the one that the subscribers are subscribed to.

![alt text](rabbitmq.png)