# Backend-Interview-Question
CAP Theorem:~
The CAP theorem states that it is not possible to guarantee all three of the desirable properties – consistency, availability, and partition tolerance at the same time in a distributed system with data replication. 

The theorem states that networked shared-data systems can only strongly support two of the following three properties: consistency, availability and partial tolerance.


PACELC theorem:~

The PACELC theorem is an extension to the CAP theorem. It states that in case of network partitioning (P) in a distributed computer system, one has to choose between availability (A) and consistency (C) (as per the CAP theorem), but else (E), even when the system is running normally in the absence of partitions, one has to choose between latency (L) and consistency (C).

Q. What is meant by eventual consistency?
Ans. Eventual Consistency is a guarantee that when an update is made in a distributed database, that update will eventually be reflected in all nodes that store the data, resulting in the same response every time the data is queried

Q. What do you mean by strong consistency?
Ans. Strong Consistency simply means the data must be strongly consistent at all times. All the server nodes across the world should contain the same value as an entity at any point in time. And the only way to implement this behavior is by locking down the nodes when being updated. 
Q. What are the different types of databases?
Ans. https://www.matillion.com/resources/blog/the-types-of-databases-with-examples 

Q. What are message queues used for?
Ans. Message queues allow different parts of a system to communicate and process operations asynchronously. A message queue provides a lightweight buffer which temporarily stores messages, and endpoints that allow software components to connect to the queue in order to send and receive messages.

Q. What is the purpose of a reverse proxy?
Ans. A reverse proxy ultimately forwards user/web browser requests to web servers. However, the reverse proxy server protects the web server's identity. This type of proxy server also moves requests strategically on behalf of web servers, typically to help increase performance, security, and reliability.

Q. What is TLS and how does it work?
Ans. Transport Layer Security (TLS) encrypts data sent over the Internet to ensure that eavesdroppers and hackers are unable to see what you transmit which is particularly useful for private and sensitive information such as passwords, credit card numbers, and personal correspondence.

Q. What is Docker? Why do we use it?
Ans. Docker is an open source containerization platform. It enables developers to package applications into containers—standardised executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment.

Q. What are webhooks used for?
Ans. A webhook is a lightweight API that powers one-way data sharing triggered by events. Together, they enable applications to share data and functionality, and turn the web into something greater than the sum of its parts. APIs and webhooks both allow different software systems to sync up and share information.

Q. Which service by Amazon Web Services (AWS) can you use for Queues?

Ans. Amazon Simple Queue Service (SQS)

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

Q. What does Pub Sub mean?
Ans. Publish/subscribe messaging
Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic.

Q.What is S3 Service in AWS? What is the AWS S3 service used for?
Ans. Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.

Q. What is EC2 Instance in AWS?

Ans. An Amazon EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2) for running applications on the Amazon Web Services (AWS) infrastructure.

Q. What is Cloudfront in AWS?

Ans. Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as . html, . css, . js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centres called edge locations.


Q. What is Route 53 In AWS?

Ans. Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.

Q. What are ELBs in AWS?

Ans. Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances in one or more Availability Zones (AZs).
