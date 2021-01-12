---
permalink: /industryProject/
title: "Industry Projects"
author_profile: true
redirect_from: 
  - /md/
  - /industryProject.html
---

## E-commerce System Development Based on Microservices
* Duration: Sep – Nov 2020
* Institution: Carnegie Mellon University
* Main Tasks:
  * Developed an e-commerce system with high stability for high-concorrency requests based on the Spring Cloud framework of Java. Used Eureka as the service registration and discovery center, Zuul as the gateway, Feign as the method to invoke microservices, and dbproxy as the microserice module to store the data.
  * Used the Redis-based stock deduction method when generating orders. Adopted the distributed locks with Redis to slove the overselling problem.
  * Employed the transactional message model in RocketMQ to update the database asynchronously in order to achieve the distributed BASE theory. In each APIs, used the Chain of Responsibility Pattern to simplify the data verification logic.
  * Utilized MySQL and HBase to store business and pipelining data respectively. Constructed multi-level caches with Guava and Redis to reduce the response delay of the static data and slove cache penetration and avalanche problems. Built the seckilling token and limitation model, supplemented by the token bucket algorithm, to realize the traffic peak clipping.
  * Used Elasticsearch to realize the function of searching the specific item. Customized the IK tokenizer to make the system support synonym discrimination. Used the recall strategy influenced by part of speech model to strengthen the understanding of the system to words.
