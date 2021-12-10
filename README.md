## Exploring Integrated Developer Experience for Devs, SREs & Cloud Infrastructure

> The CAP theorem of service APIs. You get functionality earlier, and eventual consistency later, because development teams are partitioned. -- https://twitter.com/adrianco/status/1466463836349763585

Expanding the horizon & span across all of the technology companies driving towards "Public" spaces building Platforms & ecosystems, wondering [Search like](https://www.google.com/search/howsearchworks/) Integrated Developer experience (**New IDE**) is a way to adddress the challenges, more data below:

1. Portals:
> "Connect" - But, the data ecosystem is vast, and no one vendor can accomplish everything. Every enterprise has a multitude of tools and data sources that need to be connected, secured, and governed to allow every user within an organization to find, use, and share data-driven insights. Stitching everything together has historically been a burden on the customer and partners, making it very complicated and expensive to execute at any scale. Partner Connect helps you connect your Azure Databricks workspace to selected partner solutions within minutes. If you do not have an account with a partner, Partner Connect helps you create a trial account with them.
  - Databricks on Azure: [Blog](https://databricks.com/blog/2021/11/18/now-generally-available-introducing-databricks-partner-connect-to-discover-and-connect-popular-data-and-ai-tools-to-the-lakehouse.html) / [Docs](https://docs.microsoft.com/en-us/azure/databricks/integrations/partners#partner-connect)
  - Cataloging the Sprawl: [Integrations](https://github.com/backstage/community) 
    - [Universe 1 - Pulumi](https://www.pulumi.com/registry/)
    - [Uinverse 2 - Dagger](https://dagger.io/)
3. Public & Community - [Collaboration - Git, GitUniverse is growing with UX & Workflows](https://next.github.com/)
4. Landscapes - [Evolving hundreds of thousands of of Products & Infrastructure](https://landscapes.dev/)
5. Code Navigation - Semantic Understanding is improving, Ex: [SourceGraph](https://sourcegraph.com/) | [GitHub Code Search](https://github.blog/2021-12-08-improving-github-code-search/)

### 1.Products - UI/UX Web, Mobile, Data, APIs, Desktop, Console, Voice, AR/VR, ...

- SaaS:
  - Explore - [World of APIs](https://www.postman.com/explore) | [State of the APIs](https://www.postman.com/state-of-api/)
  - Build - [Stripe](https://stripe.com/docs) | [Plaid](https://plaid.com/docs/) | [Shopify](https://shopify.dev/api) | [Twilio](https://www.twilio.com/docs) + [Segment](https://segment.com/docs/) | ...

- **Dev** - Design / Modeling / Tools / Frameworks
  
  - App: https://www.prisma.io/dataplatform | https://temporal.io/ |
  
  - IDE:
    - Notebooks - https://jupyter.org/ | https://colab.research.google.com/ |
    - VS Code - https://github.dev/ | https://vscode.dev/ 
 
  - APIs - Open source API specifications OpenAPI, AsyncAPI, and JSON Schema; Linter, Breaking change detector, generator ...
    - OpenAPI -  https://swagger.io/ | https://stoplight.io/studio/
    - GraphQL -  https://sandbox.amplifyapp.com/getting-started | https://www.apollographql.com/studio/develop/ | https://graphql.stepzen.com/ | https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql | https://hopper.wundergraph.com/ |
    - Protocol Buffers - https://buf.build/
    - AsyncAPI: https://www.asyncapi.com/
    - FW's: https://linkedin.github.io/rest.li/
  
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
  * [How eBPF will solve Service Mesh - Goodbye Sidecars](https://isovalent.com/blog/post/2021-12-08-ebpf-servicemesh)

7. **Linux / Unix**
* Evolution of the Unix System Architecture ("Besides historical details, it also has a number of interesting lessons for software architecture evolution") - https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8704965
 


