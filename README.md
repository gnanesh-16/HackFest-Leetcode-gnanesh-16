---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: false
  outline:
    visible: true
  pagination:
    visible: true
---

# DATABASE - Redis &&

## Difference BTW REDIS & MongoDb&#x20;

The main differences between Redis and MongoDB lie in their primary functions and data storage approaches.

* Redis is primarily an in-memory data store that can be used as a database, cache, or message broker[3](https://backendless.com/redis-what-it-is-what-it-does-and-why-you-should-care/)[4](https://redis.io/blog/redis-cache-vs-redis-primary-database-in-90-seconds/). It excels in fast performance, flexibility, and ease of use. Redis is often used for caching web pages, reducing server load, and as a session store due to its speed and in-memory nature. It supports various data structures and is known for its scalability and high read/write capabilities.
* MongoDB, on the other hand, is a document-oriented database that stores data in JSON-like documents with a dynamic and flexible schema[1](https://stackshare.io/redis/alternatives). It is designed for high availability and scalability, with features like built-in replication and auto-sharding. MongoDB is suitable for applications requiring structured data storage and complex queries.

In summary, Redis is more commonly used for caching and in-memory data storage, while MongoDB is favored for its document-oriented approach and suitability for structured data storage and complex queries.
