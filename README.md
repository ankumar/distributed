# Applications - Web, Mobile, API, Voice, Desktop & Console

**Stateless & Stateful services:**

1. Synchronous Serving System

2. Asynchronous, Event Driven System

* Global Load Balancing, DNS-based & SDN Anycast

* Caching & CDN

* CAP Theorem

* Edge & Cloud Computing

# Infrastructure
 
1. **"The Log"**

* [Kafka Improvement Proposals](https://cwiki.apache.org/confluence/display/KAFKA/Kafka+Improvement+Proposals)
  * [A Raft Protocol for the Metadata Quorum](https://cwiki.apache.org/confluence/display/KAFKA/KIP-595%3A+A+Raft+Protocol+for+the+Metadata+Quorum)
  
* Vectorized Redpanda - Kafka® API compatible, C++ Implementation

* Write Ahead Log - https://wepay.github.io/waltz/docs/introduction

* Benchmarking - https://www.confluent.io/blog/kafka-fastest-messaging-system/

2. **Purpose-built Databases**

* Key/Value - Cassandra; ScyllaDB, Apache Cassandra in C++
* Distributed SQL - 

3. **Data Warehouse / Data Lake**

* Data Processing - </>
* Storage - https://delta.io/
 
4. **Availability, Regions & Zones**

# References

## Small & Medium scale systems

## Large scale systems

**1. Building:**

[@scale](https://atscaleconference.com/)

* [Fail at Scale](https://queue.acm.org/detail.cfm?id=2839461)
* [Zero downtime deployments at Facebook](https://dl.acm.org/doi/abs/10.1145/3387514.3405885)

* [Client-side load balancing technique](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/daperture-load-balancer.html)

* [DNS based GSLB](https://dropbox.tech/infrastructure/intelligent-dns-based-load-balancing-at-dropbox)

* [Influence of heavy-tailed distributions on load balancing](http://www.cs.cmu.edu/~harchol/ISCA15show.pdf)

**2. Renting:**

> hyperscalers (Amazon, Google and Microsoft) have moved far outside their initial niche of standard IT infrastructure services. In addition to providing services for developers to reduce time-to-market, they have built specialist services targeted at the major technology trends such as blockchain, 5G, machine learning, artificial intelligence and digital identity. Moreover, they are adding many industry-focused solutions.

* Cloud Native DB's - https://db.cs.cmu.edu/archived-events/
  * **Distributed SQL** - GCP Spanner,  YugaByte DB (PostgreSQL), MariaDB SkySQL, CockroachDB, ...
  * **Key/Value** - Migrating Amazon retail services to NoSQL, **DynamoDB** ; re:Invent & Twitch Talks from Rick Houlihan 
  
