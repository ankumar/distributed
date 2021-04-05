# 1. Products - Web, Mobile, Data, APIs, Desktop, Console, Voice, AR/VR

For Improvements Ask End Users, Developers to be critical & actively seek Feedback.

**Stateless & Stateful services:**
* Global Load Balancing, DNS-based & SDN Anycast
* Caching & CDN
* CAP Theorem
* Edge & Cloud Computing
* Availability, Regions & Zones

1. Synchronous, Serving System 
2. Asynchronous, Event Driven System

# 2. Infrastructure - Compute, Storage & Network

Large-scale distributed infrastructure are:
 
1. **"The Log"**

* Kafka:
  * Benchmarking - https://www.confluent.io/blog/kafka-fastest-messaging-system/
  * [Kafka Improvement Proposals](https://cwiki.apache.org/confluence/display/KAFKA/Kafka+Improvement+Proposals)
    * Tiered Storage
    * [Replace Zookeeper - A Raft Protocol for the Metadata Quorum](https://cwiki.apache.org/confluence/display/KAFKA/KIP-595%3A+A+Raft+Protocol+for+the+Metadata+Quorum)
  
* [Vectorized](https://vectorized.io/) **Redpanda** - Kafka® API compatible, C++ Implementation
* Write Ahead Log - https://wepay.github.io/waltz/docs/introduction

2. **Purpose-built Databases**

* Key/Value - Cassandra; ScyllaDB, Apache Cassandra in C++
* Distributed SQL 

3. **Data Warehouse / Data Lake**

* Data Processing - </>
* Storage - https://delta.io/
 
# 3. References

## Small & Medium scale systems

## Large scale systems

**1. Renting:**

![](https://github.com/ankumar/Architecture/blob/main/images/Annual%20CAPEX.png)

Source: https://www.platformonomics.com/2021/02/follow-the-capex-cloud-table-stakes-2020-retrospective/

> hyperscalers (Amazon, Google and Microsoft) have moved far outside their initial niche of standard IT infrastructure services. In addition to providing services for developers to reduce time-to-market, they have built specialist services targeted at the major technology trends such as blockchain, 5G, machine learning, artificial intelligence and digital identity. Moreover, they are adding many industry-focused solutions.

* Cloud Native DB's - https://db.cs.cmu.edu/archived-events/
  * **Distributed SQL** - GCP Spanner,  YugaByte DB (PostgreSQL), MariaDB SkySQL, CockroachDB, ...
  * **Key/Value** - Migrating Amazon retail services to NoSQL, **DynamoDB** ; re:Invent & Twitch Talks from Rick Houlihan 
  
* **Providers**
  * [Google Cloud Run - FAQ](https://github.com/ahmetb/cloud-run-faq)

**2. Building:**

[@scale](https://atscaleconference.com/)

* [LogDevice](https://logdevice.io/)
* [Mcrouter (pronounced mc router)](https://github.com/facebook/mcrouter)

---

**1. Blogs:**

* [Client-side load balancing technique](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/daperture-load-balancer.html)
* [DNS based GSLB](https://dropbox.tech/infrastructure/intelligent-dns-based-load-balancing-at-dropbox)
* [Shard Manager](https://engineering.fb.com/production-engineering/scaling-services-with-shard-manager/)
* [Consensus Algorithms at Scale](https://www.planetscale.com/blog/blog-series-consensus-algorithms-at-scale-1)
* [Steve Yegge’s Google Platforms Rant](https://gist.github.com/chitchcock/1281611)
* [Excel is still going strong, just became a Turing-complete programming language!](https://www.microsoft.com/en-us/research/blog/lambda-the-ultimatae-excel-worksheet-function/)

---

**2. Papers:**

* [The Datacenter as a Computer](http://bnrg.eecs.berkeley.edu/~randy/Courses/CS294.F09/wharehousesizedcomputers.pdf)
* [Fail at Scale](https://queue.acm.org/detail.cfm?id=2839461)
* [Zero downtime deployments at Facebook](https://dl.acm.org/doi/abs/10.1145/3387514.3405885)
* [Pitfalls of Anycast](https://www.usenix.org/sites/default/files/conference/protected-files/srecon17emea_slides_murali_suriar.pdf)
* [Influence of heavy-tailed distributions on load balancing](http://www.cs.cmu.edu/~harchol/ISCA15show.pdf)
* [Akamai DNS: Providing Authoritative Answers to the World’s Queries](https://groups.cs.umass.edu/ramesh/wp-content/uploads/sites/3/2020/07/sigcomm2020-final289.pdf)
* [Monarch: Google’s Planet-Scale In-Memory Time Series Database](http://www.vldb.org/pvldb/vol13/p3181-adams.pdf)
* [Read-Write Quorum Systems Made Practical](https://mwhittaker.github.io/publications/quoracle.html)

---

**3. Tech Talks:**

* [Quarantine Database Tech Talks (2020)](https://www.youtube.com/playlist?list=PLSE8ODhjZXjagqlf1NxuBQwaMkrHXi-iz)
* [New Directions in Cloud Programming](https://www.youtube.com/watch?v=FeRg-7Sr1L8)
