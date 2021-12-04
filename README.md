## Exploring Integrated Developer Experience for Devs, SREs & Cloud Infrastructure

### 1.Products - UI/UX Web, Mobile, Data, APIs, Desktop, Console, Voice, AR/VR, ...

- SaaS: 
  - Dev: https://sandbox.amplifyapp.com/getting-started
  - APIs: https://www.postman.com/explore 
  - Docs: [Stripe](https://stripe.com/docs) | [Plaid](https://plaid.com/docs/) | [Shopify](https://shopify.dev/api) | [Twilio](https://www.twilio.com/docs) | [Segment](https://segment.com/docs/) |

- **Dev** - Design / Modeling / Tools / Frameworks
  - App - https://www.prisma.io/dataplatform :heart:
  
  - APIs - Open source API specifications OpenAPI, AsyncAPI, and JSON Schema; Linter, Breaking change detector, generator ...
    - OpenAPI -  https://swagger.io/ | https://stoplight.io/studio/
    - GraphQL - https://www.apollographql.com/studio/develop/ | https://graphql.stepzen.com/ | https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql | https://hopper.wundergraph.com/ |
    - Protocol Buffers - https://buf.build/
    - AsyncAPI: https://www.asyncapi.com/
    - FW's: https://linkedin.github.io/rest.li/
  
  - Web IDE - https://vscode.dev/ | https://github.dev/ | 
  
  - Code Generators - https://copilot.github.com/ | https://www.hofstadter.io/ | 
  
  - Auth:
     - Authentication, WHO YOU ARE
     - Authorization, WHAT YOU ARE ALLOWED TO DO 
       - https://play.authzed.com/ | https://www.osohq.com/what-is-oso

  - Data
     - Wrangling  
   
- Communities:
  - GitHub - https://octoverse.github.com/
  - Platforms for Open Source Creators - https://www.oss.fund/

### 2.Infrastructure - Utility Compute, Storage & Network

**APIs:**
* https://docs.dagger.io/reference/README :heart:

**Configuration:**
* https://docs.dagger.io/1005/what-is-cue/

**Stateless & Stateful Apps:**
1. Synchronous, Serving System 
2. Asynchronous, Event Driven System

1. Prime Days - https://aws.amazon.com/blogs/aws/prime-day-2021-two-chart-topping-days/

**Large-scale distributed infrastructure:**
 
1. **Authenticate & Authorize**

* AWS Identity - [500 million API calls EVERY SECOND](https://aws.amazon.com/blogs/aws/happy-10th-birthday-aws-identity-and-access-management/)
* Azure AD - [Manages more than 1.2 billion identities and processes over 8 billion authentications every day](https://azure.microsoft.com/en-us/services/active-directory/)

2. **"The Log"**

* [Event-Driven Architectures - The Queue vs The Log](https://jack-vanlightly.com/blog/2018/5/20/event-driven-architectures-the-queue-vs-the-log)

* Kafka:
  * Benchmarking - https://www.confluent.io/blog/kafka-fastest-messaging-system/
  * [Kafka Improvement Proposals](https://cwiki.apache.org/confluence/display/KAFKA/Kafka+Improvement+Proposals)
    * Tiered Storage
    * [Replace Zookeeper - A Raft Protocol for the Metadata Quorum](https://cwiki.apache.org/confluence/display/KAFKA/KIP-595%3A+A+Raft+Protocol+for+the+Metadata+Quorum)
  * [Vectorized](https://vectorized.io/) **Redpanda** - Kafka® API compatible, C++ Implementation
  * Write Ahead Log - https://wepay.github.io/waltz/docs/introduction
* Queue:
  * https://engineering.fb.com/2021/02/22/production-engineering/foqs-scaling-a-distributed-priority-queue/

3. **Purpose-built Databases**

Managing state - one of the hardest problem in distributed systems
* Key/Value - Cassandra; ScyllaDB, Apache Cassandra in C++
* Distributed SQL 
 
 * AI/ML:
    * Anyscale / Ray - https://www.youtube.com/watch?v=dn8hu2sgRWU
 
 * Studios: 
    * https://www.sensedeep.com/blog/posts/stories/dynamodb-studio.html
    * https://dynobase.dev/
    * https://cloud.prisma.io/
      * Mac/Linux/Windows - https://www.prisma.io/studio

* Database:
  * [The PlanetScale Workflow](https://docs.planetscale.com/concepts/planetscale-workflow)
  * [DynamoDB - Single-Table Modeling](https://amazondynamodbofficehrs.splashthat.com/)
  * [Prisma - "application models"](https://www.prisma.io/docs/concepts/overview/what-is-prisma/data-modeling)
  

* Metadata: 
  * [LinkedIn GMA](https://github.com/linkedin/datahub-gma/blob/master/docs/how/metadata-modelling.md)
  * [OpenMetadata](https://docs.open-metadata.org/openmetadata/schemas)

* Things & More:
  * [Azure opendigitaltwins](https://github.com/Azure/opendigitaltwins-building)
  * [AWS IoT Things Graph](https://docs.aws.amazon.com/thingsgraph/latest/ug/iot-tg-whatis.html)
  * [Google Digital Buildings](https://google.github.io/digitalbuildings/)
  * [Smart Data Models](https://smartdatamodels.org/)

4. **Data Warehouse / Data Lake**

* Storage - [Cloud, S3](https://www.allthingsdistributed.com/2021/03/happy-15th-birthday-amazon-s3.html) / Open Source https://delta.io/
* Data Processing - </>

5. **Networking**

* Kubernetes - https://cloud.google.com/blog/products/containers-kubernetes/new-gke-gateway-controller-implements-kubernetes-gateway-api / https://smi-spec.io/#ecosystem

6. **Telemetry**
* eBPF - https://github.com/cloudflare/ebpf_exporter / https://engineering.fb.com/2021/04/27/developer-tools/reverse-debugging/ / https://cilium.io/

7. **Linux / Unix**
* Evolution of the Unix System Architecture ("Besides historical details, it also has a number of interesting lessons for software architecture evolution") - https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8704965
 
## All Things Distributed - References & Evolving Context

Exponential growth of Nodes/Edges:
- Apple, Stripe, Meta <-> +[AWS](https://aws.amazon.com/solutions/case-studies) 
- Walmart <-> +[Azure](https://azure.microsoft.com/en-us/resources/customer-stories/), +[GCP](https://cloud.google.com/customers)
- Shopify, Twitter <-> +GCP
- ...
- ...
- IoT <-> +\[AWS, Azure, GCP\]
- SpaceX/STARLINK <-> +GCP

- Global Load Balancing, DNS-based & SDN Anycast
- Caching & CDN
- CAP Theorem
- Edge & Cloud Computing
- Availability, Regions & Zones

**Modelling systems:**
* [TLA+](http://lamport.azurewebsites.net/tla/tla.html)
* [The P programming language](https://github.com/p-org/P)

**1. As a service:**
![](https://github.com/ankumar/Architecture/blob/main/images/Cumulative%20CAPEX.jpg)

Source: https://www.platformonomics.com/2021/02/follow-the-capex-cloud-table-stakes-2020-retrospective/

> hyperscalers (Amazon, Google and Microsoft) have moved far outside their initial niche of standard IT infrastructure services. In addition to providing services for developers to reduce time-to-market, they have built specialist services targeted at the major technology trends such as blockchain, 5G, machine learning, artificial intelligence and digital identity. Moreover, they are adding many industry-focused solutions.

* **Cloud Native DB's**
  * **Distributed SQL** - GCP Spanner,  YugaByte DB (PostgreSQL), MariaDB SkySQL, CockroachDB, ...
  * **Key/Value** - Migrating Amazon retail services to NoSQL, **DynamoDB** ; re:Invent & Twitch Talks from Rick Houlihan 

* **IAM** 
  * https://www.okta.com/ / https://auth0.com/  
  * https://www.authorizon.com/ 
  * https://authzed.com/ 
  
* **Kubernetes**
  * [Google Cloud Run - FAQ](https://github.com/ahmetb/cloud-run-faq)
  * https://www.slim.ai/

**2. Building:**

- The bottom half of the OSI reference model?
- Compute, Network, Storage
- Connected with a kernel
Example Infrastructure:
- (Compute) Server, Operating System, Container Runtime, Process
- (Storage) 💾Disk, Database, Memory
- (Network) Load Balancer, Firewall, Network Switch, Router

-- https://github.com/kris-nova/public-speaking/blob/main/presentations/2021-infrastructure-as-software/5-what-is.zomg

[@scale](https://atscaleconference.com/)

* [LogDevice](https://logdevice.io/)
* [Mcrouter (pronounced mc router)](https://github.com/facebook/mcrouter)
* https://db.cs.cmu.edu/archived-events/

---

**1. Blogs:**

* [An Introduction to Distributed Systems](https://github.com/aphyr/distsys-class)
* [the morning paper](https://blog.acolyer.org/)
* [Marc's Blog](https://brooker.co.za/blog/)
* [Client-side load balancing technique](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/daperture-load-balancer.html)
* [DNS based GSLB](https://dropbox.tech/infrastructure/intelligent-dns-based-load-balancing-at-dropbox)
* [Shard Manager](https://engineering.fb.com/production-engineering/scaling-services-with-shard-manager/)
* [Consensus Algorithms at Scale](https://www.planetscale.com/blog/blog-series-consensus-algorithms-at-scale-1)
* [Steve Yegge’s Google Platforms Rant](https://gist.github.com/chitchcock/1281611)
* [Excel is still going strong, just became a Turing-complete programming language!](https://www.microsoft.com/en-us/research/blog/lambda-the-ultimatae-excel-worksheet-function/)
* [The Distributed Operating System Void](https://nivenly.com/lib/2021-04-02-operating-system-interface/)
* [COSI - The Common Operating System Interface](https://docs.google.com/document/d/1OuwTSsSsIPefDViheK-nzaF9xSOg1Mn62mwR2FmGPu8/edit#heading=h.1grxkjflkt7d)
* [Micah Lerner](https://www.micahlerner.com/)
* [Metadata](http://muratbuffalo.blogspot.com/)

---

**2. Publications:**

* [100 Year Study on AI released its 2021 Report](https://ai100.stanford.edu/)
* [Our Journey towards Data-Centric AI: A Retrospective](https://ai.stanford.edu/blog/data-centric-ai-retrospective/)
* [Architecting the Future of Software Engineering: A National Agenda for Software Engineering Research & Development](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=741193)
* [Why AI is Harder Than We Think](https://arxiv.org/abs/2104.12871)
* [Cloud Infrastructure Services: An analysis of potentially anti-competitive practices](https://www.fairsoftwarestudy.com/)
* [From Cloud Computing to Sky Computing](https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s02-stoica.pdf)
* [Why Google Stores Billions of Lines of Code in a Single Repository](https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext)
* [The Datacenter as a Computer](http://bnrg.eecs.berkeley.edu/~randy/Courses/CS294.F09/wharehousesizedcomputers.pdf)
* [Fail at Scale](https://queue.acm.org/detail.cfm?id=2839461)
* [Zero downtime deployments at Facebook](https://dl.acm.org/doi/abs/10.1145/3387514.3405885)
* [Pitfalls of Anycast](https://www.usenix.org/sites/default/files/conference/protected-files/srecon17emea_slides_murali_suriar.pdf)
* [Influence of heavy-tailed distributions on load balancing](http://www.cs.cmu.edu/~harchol/ISCA15show.pdf)
* [Akamai DNS: Providing Authoritative Answers to the World’s Queries](https://groups.cs.umass.edu/ramesh/wp-content/uploads/sites/3/2020/07/sigcomm2020-final289.pdf)
* [Monarch: Google’s Planet-Scale In-Memory Time Series Database](http://www.vldb.org/pvldb/vol13/p3181-adams.pdf)
* [Read-Write Quorum Systems Made Practical](https://mwhittaker.github.io/publications/quoracle.html)
* [Zanzibar: Google’s Consistent, Global Authorization System](https://news.ycombinator.com/item?id=26980254)
* [Colossus - Google’s Storage Foundation](https://www.infoq.com/news/2021/04/google-colossus/)
* [Designing a Serverless Cloud-Native Database-as-a-Service Based on Apache Cassandra™](https://www.datastax.com/sites/default/files/content/whitepaper/files/2021-06/Astra%20Serverless%20Whitepaper_0.pdf)
* [Maglev: A Fast and Reliable Software Network Load Balancer](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)
* [Sizeless: Predicting the Optimal Size of Serverless Functions](https://se.informatik.uni-wuerzburg.de/software-engineering-group/staff/simon-eismann/?tx_extbibsonomycsl_publicationlist[action]=download&tx_extbibsonomycsl_publicationlist[controller]=Document&tx_extbibsonomycsl_publicationlist[fileName]=MIDDLEWARE2021___Sizeless.pdf&tx_extbibsonomycsl_publicationlist[intraHash]=ececf0bdbba4e0517d68cb7dba7423e6&tx_extbibsonomycsl_publicationlist[userName]=simon.eismann&cHash=dd84cf187c8303334c8f4fde69bed2a2)

---

**3. Tech Talks:**

* [Quarantine Database Tech Talks (2020)](https://www.youtube.com/playlist?list=PLSE8ODhjZXjagqlf1NxuBQwaMkrHXi-iz)
* [New Directions in Cloud Programming](https://www.youtube.com/watch?v=FeRg-7Sr1L8)
