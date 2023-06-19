# Pub-Sub Model
•This is an **event-based** in which, when an event occurs, we distributed it to the group of consumers without any delay and any fault in message.

•Used **kafka** as a distributed event streaming platform that transfer message from source to destination with negligible loss.

Kafka combines three key capabilities so we can implement our use cases for event streaming end-to-end with a single battle-tested solution:

1. To **publish** (write) and **subscribe** to (read) streams of events, including continuous import/export of our data from other systems.
2. To **store** streams of events durably and reliably for as long as we want.
3. To **process** streams of events as they occur or retrospectively.
   
And all this functionality is provided in a distributed, highly scalable, elastic, fault-tolerant, and secure manner. Kafka can be deployed on bare-metal hardware, virtual machines, and containers, and on-premises as well as in the cloud. You can choose between self-managing your Kafka environments and using fully managed services offered by a variety of vendors.

•Used **Zookeeper** to sync producer & consumers and used kafka Manager to mange brokers & topics into a cluster. Apache ZooKeeper is an effort to develop and maintain an open-source server which enables highly reliable distributed coordination.
