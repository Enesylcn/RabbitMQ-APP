# Introduction
This project is an example of developing an application using RabbitMQ message queue. The application includes a simple structure for sending and receiving messages.
## :beginner: About

RabbitMQ is an open-source message broker software that facilitates communication between distributed systems. It is based on the Advanced Message Queuing Protocol (AMQP) and provides a robust and scalable messaging solution.
![image](https://github.com/Enesylcn/RabbitMQ-APP/assets/86023573/42966938-6b08-44e7-a5ba-33776e546767)

### Key Features of RabbitMQ:

- **Messaging Patterns:** RabbitMQ supports various messaging patterns, including point-to-point, publish/subscribe, and request/reply.

- **Reliability:** It ensures reliable message delivery through features like message acknowledgment and durable queues.

- **Flexibility:** RabbitMQ allows for easy integration with various programming languages and platforms.

- **Scalability:** It can handle a large number of concurrent connections and scale horizontally to meet growing demands.

- **Management and Monitoring:** RabbitMQ provides a web-based management interface and supports monitoring tools to track message queues and system health.

### :notebook: Pre-Requisites
Before running the application, make sure you have the following software installed on your machine:

- [Node.js and npm](https://nodejs.org/): JavaScript runtime and package manager for building the frontend.

- [.NET Core SDK](https://dotnet.microsoft.com/download): Software development kit for building the backend.

- [RabbitMQ Server](https://www.rabbitmq.com/download.html): A message broker software for handling message queues.

Ensure that you have these dependencies installed, as they are necessary for the proper functioning of the RabbitMQ-APP.

## :zap: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/Enesylcn/RabbitMQ-APP

# Go into the repository
$ cd RabbitMQ-APP

# Install dependencies
$ npm install

# Run the app
$ npm start
```
##  :page_facing_up: Resources
- https://www.youtube.com/watch?v=wZbX_Qh8zbI&t=3444s
- https://www.amqp.org/
- https://chat.openai.com/
- https://medium.com/devopsturkiye/rabbitmq-genel-bakis-76824f890fd0


##  :camera: Gallery
- The publisher named "queue1", which produces a message every half a second, is run on RabbitMQ, and the consumer with the same name pulls these messages from the queue.
  ![Consumer_Queue2](https://github.com/Enesylcn/RabbitMQ-APP/assets/86023573/fe9c6ecb-1eba-4bab-bc1c-711ff10a051a)
- The moment when two publishers and four consumers connected to the same router are working with these two different publishers.
  ![allConusmer](https://github.com/Enesylcn/RabbitMQ-APP/assets/86023573/9da7f503-d3d3-4b8a-abd0-c68cf4fd7535)


