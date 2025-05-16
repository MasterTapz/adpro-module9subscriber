### a. What is AMQP?

AMQP, short for Advanced Message Queuing Protocol, is an open messaging protocol designed for message-oriented middleware. It facilitates communication between distributed systems by allowing them to exchange messages via queues. AMQP is known for supporting asynchronous, reliable, and loosely coupled message delivery, making it ideal for scalable and fault-tolerant architectures.

---

### b. What does guest\:guest\@localhost:5672 mean?

This string breaks down as follows:

* The first `guest` refers to the username used to authenticate with the broker.
* The second `guest` represents the corresponding password.
* `localhost` specifies that the broker is running on the local machine.
* `5672` is the default port number assigned for AMQP services.

Therefore, `amqp://guest:guest@localhost:5672` is a Uniform Resource Identifier (URI) that tells the application to connect to a message broker (such as RabbitMQ) hosted on the same computer, using the `guest` credentials over port 5672.


