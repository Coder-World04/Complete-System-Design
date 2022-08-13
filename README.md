# Complete-System-Design
This repository contains everything you need to become proficient in System Design

Topics you should know in System Design 

1. [System design basics](https://medium.com/coders-mojo/complete-system-design-series-part-1-45bf9c8654bc)

2. [Horizontal and vertical scaling](https://medium.com/coders-mojo/complete-system-design-series-part-2-922f45f2faaf)

3. [Load balancing and Message queues](https://medium.com/coders-mojo/part-3-complete-system-design-series-e1362baa8a4c)

4. [High level design and low level design, Consistent Hashing, Monolithic and Microservices architecture](https://medium.com/coders-mojo/part-4-complete-system-design-series-138bc9fbcfc0)

5. [Caching, Indexing, Proxies](https://medium.com/coders-mojo/part-5-complete-system-design-series-4b9b04f23608)

6. [Networking, How Browsers work, Content Network Delivery ( CDN)](https://medium.com/coders-mojo/part-6-complete-system-design-series-59a2d8bbf1ed)

7. [Database Sharding, CAP Theorem, Database schema Design](https://medium.com/coders-mojo/part-7-complete-system-design-series-1bef528923d6)

8. [Concurrency, API, Components + OOP + Abstraction](https://medium.com/coders-mojo/part-8-complete-system-design-series-57bc88433c8e)

9. [Estimation and Planning, Performance](https://medium.com/coders-mojo/part-9-complete-system-design-series-df975c85ec51)

10. [Map Reduce, Patterns and Microservices](https://medium.com/coders-mojo/most-popular-system-design-questions-mega-compilation-45218129fe26)

------------------------------

** Part 1 of System Design Made Easy Series**

In the part 1, we covered what and why of System Design and the important topics that you should know. System Design is mostly an open ended concept and most of the questions can be answered in different degrees and aptitudes. In layman’s language, system design is about —

Architecture + Data + Applications

[Learn what is system design and why it’s important, how they work and how to use them in your system design interviews in part 1 ](https://medium.com/coders-mojo/complete-system-design-series-part-1-45bf9c8654bc)


------------------------------


**Part 2 of System Design Made Easy Series**

In the part 2, we covered —

1. System design basics

2. Horizontal and Vertical Scaling with an example

In technical words, scalability is a the technique/process of adding/removing infrastructure/resources required by applications to better serve/accommodate increased/decreased demand/growth. We also covered the tradeoffs of horizontal and vertical scaling.

[Learn why good understanding of system design basics and horizontal and vertical scaling are important, how they work and how to use them in your system design interviews in part 2
](https://medium.com/coders-mojo/complete-system-design-series-part-2-922f45f2faaf)

------------------------------

**Part 3 of System Design Made Easy Series**

In the part 3, we covered system design’s most important concepts —

1. Load Balancing

2. Message Queues

Load balancing is a technique of distributing tasks over a set of servers/machines to improve the performance, throughput, high availability, redundancy and reliability of the system. Not just it enables horizontal scaling but also dynamic resizing/scaling.

Message queues are nothing bit temporary buffers placed between users/applications and servers to store the message requests and process them in FIFO order asynchronously until the requests/messages are delivered to the desired server.

We also covered the tradeoffs of the different techniques.

[Learn why load balancing and message queues are important, how they work and how to use them in your system design interviews in part 3](https://medium.com/coders-mojo/part-3-complete-system-design-series-e1362baa8a4c)

------------------------------

**Part 4 of System Design Made Easy Series**

In the part 4, we covered

1. High level design and Low level design

2. Monolithic and microservices architecture and which one to choose and when?

3. Consistent Hashing

High level Design (HLD) describes the overall architecture of the application and covers functionality of each module of the system very briefly. LLD details the functional logic of the each module in the system.

Monolithic architecture — consists of single code base with multiple modules and it’s easier and faster to deploy. Microservices architecture — consists of individual service units with each service being responsible for exactly one functionality. It’s relatively complex and time taking to deploy.

Consistent hashing is a technique to divide keys/data between multiple servers/machines using a hash function ( key — value).

[Learn why high level design and low level design, Monolith and microservices architecture and consistent hashing are important, how they work and how to use them in your system design interviews in part 4](https://medium.com/coders-mojo/part-4-complete-system-design-series-138bc9fbcfc0)


------------------------------

**Part 5 of System Design Made Easy Series**

In the part 5, we covered —

1. Caching

2. Indexing

3. Proxies

Caching is a technique which is based on the principal of locality — stores the copies of most frequently used/accessed data in a small and faster memory to improve Data retrieval times, Compute costs, User Experience and Throughput.

Indexing helps in Improving the speed of data access/retrieval, Reducing the number of expensive I/O operations, Providing better organization and management of multilevel data records.

Proxies play an important role of coordinating user requests, handling concurrent requests, filtering user request, transforming user requests by adding an additional layer of encryption or header information or compression information and then forwarding the user request to the server.

[Learn why Caching, Indexing and Proxies are important, how they work and how to use them in your system design interviews in part 5
](https://medium.com/coders-mojo/part-5-complete-system-design-series-4b9b04f23608)


------------------------------

**Part 6 of System Design Made Easy Series**

In the part 6, we covered —

1. Networking

2. How Browsers work

3. Content Network Delivery ( CDN)

Networking is nothing but interconnected devices that can exchange data-messages and share resources amongst themselves/with outside world based in the system protocols/rules, technologies and algorithms that govern these devices inner workings.

Browsers are used to present the website/resource you would like to visit say, for example google.com by sending the request to the server and displaying it on their browser window.

Content Network Delivery caters to the users by serving their requests by quickly transferring the data back and forth.

[Learn why networking, browsers working and CDN are important, how they work and how to use them in your system design interviews in part 6](https://medium.com/coders-mojo/part-6-complete-system-design-series-59a2d8bbf1ed)

------------------------------

**Part 7 of System Design Made Easy Series**

In the part 7, we covered —

1. Database Sharding

2. CAP Theorem

3. Database schema Design

Sharding is the technique to database partitioning that separates large and complex databases into smaller, faster and distributed databases for higher throughput operations.

CAP theorem lets you determine how you want to handle your distributed databases with there is possibility of inconsistencies, unavailability and connection errors/failures/outrage.

Database schema Design lets you organize data into separate entities and establish and organize the relationships between different entities.

[Learn why database sharding, CAP theorem and Database Schema Design are important, how they work and how to use them in your system design interviews in part 7](https://medium.com/coders-mojo/part-7-complete-system-design-series-1bef528923d6)

------------------------------

**Part 8 of System Design Made Easy Series
**

In the part 8 , we covered —

1. Concurrency

2. API

3. Components + OOP + Abstraction

Concurrency is the process in which multiple computations/operations/process happen/execute in parallel/concurrently.

API is an acronym for application programming interface which provides a way to two or more programs to communicate, work together despite different configurations, architectures, resources etc

Components in the system design are building blocks designed to coordinate, cooperate, reuse and work well with other components of the same/different systems. They can be as simple as visual components or internal components/backend components.

[Learn why concurrency, API and Components + OOP + Abstraction are important, how they work and how to use them in your system design interviews in part 8
](https://medium.com/coders-mojo/part-8-complete-system-design-series-57bc88433c8e)

------------------------------

**Part 9 of System Design Made Easy Series**

In the part 9 , we covered —

1. Planning and Estimation

2. Performance

Planning and estimation( numbers) and performance are very important concepts ( concept that you should be able to demonstrate well when asked).

[Learn why Planning, estimation( numbers) and performance are important, how they work and how to use them in your system design interviews in part 9](https://medium.com/coders-mojo/part-9-complete-system-design-series-df975c85ec51)

------------------------------

**Part 10 of System Design Made Easy Series**

In the part 10, we covered —

1. Map Reduce

2. Patterns and Microservices

In system design, map reduce ( Hadoop systems) is a batch processing technique in which the engine takes huge amounts of data, processes ( map and reduce) and gives the output.

In system design, microservices architecture is used to build enterprise level applications which helps in structuring the whole application as a collection of tiny autonomous, self contained services for each task ( service) that you want/are allowed to perform.

[Learn why map reduce, patterns and microservices are important, how they work and how to use them in your system design interviews in part 10](https://medium.com/coders-mojo/part-10-complete-system-design-series-523b4dd978bf)

------------------------------

**Most Popular System Design Questions — Mega Compilation**

In this post. we covered the most popular/important system design questions that you should practice to build a thorough understanding of how large systems are designed.

Popular Questions : [Link](https://medium.com/coders-mojo/most-popular-system-design-questions-mega-compilation-45218129fe26)

