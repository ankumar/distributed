## Exploring Integrated Developer Experience for Devs, SREs & Cloud Infrastructure

> The CAP theorem of service APIs. You get functionality earlier, and eventual consistency later, because development teams are **partitioned**. -- https://twitter.com/adrianco/status/1466463836349763585

Partitions: **"Entropy always increases"**, How about **High Consistency?**

Universe 1 - **Developer Experience**, https://octoverse.github.com/ ; Data Science by JetBrains: [We Downloaded 10,000,000 Jupyter Notebooks From Github - This Is What We Learned](https://blog.jetbrains.com/datalore/2020/12/17/we-downloaded-10-000-000-jupyter-notebooks-from-github-this-is-what-we-learned/). 
 
Universe 2 - **Cloud Infrastructure**, [Infrastructure as Software](https://www.reddit.com/r/kubernetes/comments/nz9fxd/infrastructure_as_software_vs_infrastructure_as/)
    
Universe 3 - **Communities**, Software development in Public spaces Open Source, GitHub, Enterprise & SaaS, TechBlogs 
  
## Cataloging Sprawl 
 
### 1. Product on Products 

- (RE) BUILD IDE:
  - SaaS:
    - Foundation - [World of APIs](https://www.postman.com/explore) | [State of the APIs](https://www.postman.com/state-of-api/)
      - [Stripe](https://stripe.com/docs) | [Plaid](https://plaid.com/docs/) | [Shopify](https://shopify.dev/api) | [Twilio](https://www.twilio.com/docs) + [Segment](https://segment.com/docs/) | 
      
  - DESIGN & TOOLS:
    - More of the Web - https://github.dev/ | https://vscode.dev/ 
    
    - Internal Company Portals - [Plugins 1](https://backstage.io/plugins) / [Plugins 2](https://roadie.io/backstage/plugins/) / [Community](https://github.com/backstage/community) / [Adopters](https://github.com/backstage/backstage/blob/master/ADOPTERS.md)
    
    - Code & Search - [SourceGraph](https://sourcegraph.com/) | [GitHub Code Search](https://github.blog/2021-12-08-improving-github-code-search/) | [GitLab](https://docs.gitlab.com/ee/integration/)
      - [Semantic Understanding](https://github.blog/2021-12-09-introducing-stack-graphs/)
    
    - Apps - https://www.prisma.io/dataplatform | https://temporal.io/ | ...
    
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
    
    - Auth: Authentication - WHO YOU ARE / Authorization - WHAT YOU ARE ALLOWED TO DO 
      - [Ory](https://medium.com/@oryteam?p=c27702055a31) | [authzed](https://play.authzed.com/) | [Oso](https://www.osohq.com/what-is-oso)

  - Security: 

- Data:
  - SaaS:
    - Foundation - [Models](https://openai.com/api/)
  - Notebooks - https://jupyter.org/ | https://colab.research.google.com/ | https://datalore.jetbrains.com/
  - Registry & Metadata:
    - [DataHub](https://datahubproject.io/), [OpenLineage](https://openlineage.io/), [](), [](), [](), [](), [](), 
  - "Flows":
    - [MLflow](https://mlflow.org/), [Kubeflow](https://www.kubeflow.org/), [Metaflow](https://metaflow.org/), [Roboflow](https://roboflow.com/), [](), [](), [](), [](), [](), [](), []()
    - [dbt](https://www.getdbt.com/), [Dagster](https://dagster.io/), [Airflow](https://www.astronomer.io/), [](), [](), [](), [](), [](), [](), [](), []()
    - [Great Expectations](https://greatexpectations.io/)
> "Connect" - But, the data ecosystem is vast, and no one vendor can accomplish everything. Every enterprise has a multitude of tools and data sources that need to be connected, secured, and governed to allow every user within an organization to find, use, and share data-driven insights. Stitching everything together has historically been a burden on the customer and partners, making it very complicated and expensive to execute at any scale. Partner Connect helps you connect your Azure Databricks workspace to selected partner solutions within minutes. If you do not have an account with a partner, Partner Connect helps you create a trial account with them. -- Databricks (We ❤️  to simplify things. ) on Azure: [Blog](https://databricks.com/blog/2021/11/18/now-generally-available-introducing-databricks-partner-connect-to-discover-and-connect-popular-data-and-ai-tools-to-the-lakehouse.html) / [Docs](https://docs.microsoft.com/en-us/azure/databricks/integrations/partners#partner-connect)
    
### 2. Cloud Infrastructure - Utility Compute, Storage & Network

**APIs:**

- [Pulumi](https://www.pulumi.com/registry/) 
- [Dagger](https://dagger.io/)
  - https://docs.dagger.io/reference/README :heart: 

**CUE:**
> CUE is an open source language, with a rich set of APIs and tooling, for defining, generating, and validating all kinds of data: configuration, APIs, database schemas, code, … you name it. -- https://cuelang.org/
* https://docs.dagger.io/1005/what-is-cue/
* https://cuetorials.com/

### 3. Communities - 

- [It Takes a Community;The Open-source Challenge](https://queue.acm.org/detail.cfm?id=3501361)
  - [Velocity reports for 2021](https://github.com/cncf/velocity)
  - Platforms for Open Source Creators - https://www.oss.fund/
  - [F(Meta)](https://opensource.fb.com/) [A](https://aws.amazon.com/opensource/?blog-posts-content-open-source.sort-by=item.additionalFields.createdDate&blog-posts-content-open-source.sort-order=desc) [A](https://opensource.apple.com/) [N](https://netflix.github.io/) [G](https://opensource.google/)

- GitHub - https://octoverse.github.com/
  - Need more Collaboration across Git products like this? https://next.github.com/
  - [Tracking the top 100 software repos on GitHub](https://ght.creativemaybeno.dev/)

- Landscapes - [Evolving Products & Infrastructure](https://landscapes.dev/)
  - Verticals - [FinTech](https://developer.gs.com/discover/home) | ... | ... | ...
 



