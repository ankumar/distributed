## Exploring Integrated Developer Experience for Devs, SREs & Cloud Infrastructure

> The CAP theorem of service APIs. You get functionality earlier, and eventual consistency later, because development teams are **partitioned**. -- https://twitter.com/adrianco/status/1466463836349763585

Meta Partitions:

Universe 1 - **Developer Experience**, More User research? https://octoverse.github.com/, Data Science by JetBrains: [We Downloaded 10,000,000 Jupyter Notebooks From Github - This Is What We Learned](https://blog.jetbrains.com/datalore/2020/12/17/we-downloaded-10-000-000-jupyter-notebooks-from-github-this-is-what-we-learned/)
 
Universe 2 - **Cloud Infrastructure**, [Infrastructure as Software](https://www.reddit.com/r/kubernetes/comments/nz9fxd/infrastructure_as_software_vs_infrastructure_as/)
    
Universe 3 - **Communities**, Software development in Public spaces like Linux Foundation, GitHub, TechBlogs etc. 
  
## Cataloging Sprawl 
 
### 1. Products - UI/UX Web, Mobile, Data, APIs, Desktop, Console, Voice, AR/VR, ...

- SaaS:
  - Explore - [World of APIs](https://www.postman.com/explore) | [State of the APIs](https://www.postman.com/state-of-api/)
  - Build - [Stripe](https://stripe.com/docs) | [Plaid](https://plaid.com/docs/) | [Shopify](https://shopify.dev/api) | [Twilio](https://www.twilio.com/docs) + [Segment](https://segment.com/docs/) | ...
  
- **Dev** - Design / Modeling / Tools / Primitives / Frameworks
  
  - Build: https://www.prisma.io/dataplatform | https://temporal.io/ |
  
  - IDE:
    - Internal Company Portals - [Plugins](https://backstage.io/plugins) / [Community](https://github.com/backstage/community) / [Adopters](https://github.com/backstage/backstage/blob/master/ADOPTERS.md)
    - Notebooks - https://jupyter.org/ | https://colab.research.google.com/ | https://datalore.jetbrains.com/
    - Code Search - [SourceGraph](https://sourcegraph.com/) | [GitHub Code Search](https://github.blog/2021-12-08-improving-github-code-search/) | [GitLab](https://docs.gitlab.com/ee/integration/)
      - [Semantic Understanding](https://github.blog/2021-12-09-introducing-stack-graphs/)
    - More of the Web - https://github.dev/ | https://vscode.dev/ 
    - Studios: 
      - https://www.sensedeep.com/blog/posts/stories/dynamodb-studio.html
      - https://dynobase.dev/
      - https://cloud.prisma.io/. Mac/Linux/Windows - https://www.prisma.io/studio
 
  - APIs - Open source API specifications OpenAPI, AsyncAPI, and JSON Schema; Linter, Breaking change detector, generator ...
    - OpenAPI -  https://swagger.io/ | https://stoplight.io/studio/
    - GraphQL -  https://stargate.io/ | https://sandbox.amplifyapp.com/getting-started | https://www.apollographql.com/studio/develop/ | https://graphql.stepzen.com/ | https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql | https://hopper.wundergraph.com/ |
    - Protocol Buffers - https://buf.build/
    - AsyncAPI: https://www.asyncapi.com/
    - FW's: https://linkedin.github.io/rest.li/
  
  - Code Generators - Declarative AND/OR AI Models, https://copilot.github.com/ | https://www.hofstadter.io/ | 
    
  - Auth:
     - Authentication, WHO YOU ARE
       - [Ory](https://medium.com/@oryteam?p=c27702055a31)
     - Authorization, WHAT YOU ARE ALLOWED TO DO 
       - [authzed](https://play.authzed.com/) | [Oso](https://www.osohq.com/what-is-oso)

  - Data:
    - "Flows":
       - [MLflow](https://mlflow.org/), [Kubeflow](https://www.kubeflow.org/), [Metaflow](https://metaflow.org/), [Roboflow](https://roboflow.com/), [](), [](), [](), [](), [](), [](), []()
       - [dbt](https://www.getdbt.com/), [Dagster](https://dagster.io/), [Airflow](https://www.astronomer.io/), []()
    - Databricks (We ❤️  to simplify things. ) on Azure: [Blog](https://databricks.com/blog/2021/11/18/now-generally-available-introducing-databricks-partner-connect-to-discover-and-connect-popular-data-and-ai-tools-to-the-lakehouse.html) / [Docs](https://docs.microsoft.com/en-us/azure/databricks/integrations/partners#partner-connect)
> "Connect" - But, the data ecosystem is vast, and no one vendor can accomplish everything. Every enterprise has a multitude of tools and data sources that need to be connected, secured, and governed to allow every user within an organization to find, use, and share data-driven insights. Stitching everything together has historically been a burden on the customer and partners, making it very complicated and expensive to execute at any scale. Partner Connect helps you connect your Azure Databricks workspace to selected partner solutions within minutes. If you do not have an account with a partner, Partner Connect helps you create a trial account with them. 
    
- Communities:
  - GitHub - https://octoverse.github.com/
    - Need more Collaboration across Git products like this? https://next.github.com/
    - [Tracking the top 100 software repos on GitHub](https://ght.creativemaybeno.dev/)
  - Landscapes - [Evolving Products & Infrastructure](https://landscapes.dev/)
  - Verticals - [FinTech](https://developer.gs.com/discover/home) | ... | ... | ...
  - Platforms for Open Source Creators - https://www.oss.fund/

### 2. Cloud Infrastructure - Utility Compute, Storage & Network

**CUE:**
> CUE is an open source language, with a rich set of APIs and tooling, for defining, generating, and validating all kinds of data: configuration, APIs, database schemas, code, … you name it. -- https://cuelang.org/
* https://docs.dagger.io/1005/what-is-cue/
* https://cuetorials.com/

**APIs:**
* [Dagger](https://dagger.io/)
  * https://docs.dagger.io/reference/README :heart: 
* [Pulumi](https://www.pulumi.com/registry/) 

**Large-scale distributed infrastructure:**

Apps:
1. Amazon.com Prime Days - https://aws.amazon.com/blogs/aws/prime-day-2021-two-chart-topping-days/
 
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
 
