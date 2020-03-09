# Elements:
1. Business - **Markets**; Products & Services, **each with unique Requirements**
2. Users - **Millions of Customers**
3. Developers - **Hundreds**

Objectives:
* Many Teams, each working on different areas of the Product
* Teams need to control their own development, deployment, and scale
* Without having to co-ordinate their changes with other teams
* Development process needs to be distributed and decoupled just like our software

## Uber
### User Journey: **Drivers & Riders**
### Transportation Services / Architecture Blocks: 
* User Profile
* Accounts
* Notification
* Payment
* Maps
* Fraud
* Fare
* Routes
* Orders
* Freight
* Business
* Bikes
* Marketing
* Promotions
* ...

## WhatsApp
### User Journey: **Product & End Users**
### Messaging Services / Architecture Blocks:
* User Profile
* Text
* Voice & Video
* Notification
* Messages
* Sessions
* Camera
* Status
* Contacts
* Groups

------

# End User Applications
* Designing Modularity & Interfaces
* Decomposing an Application into Services & APIs

1. Mobile
2. Web

# Distributed Front-end & Back-end
1. Apps Structured as Independent Microservices
* Many Teams
* Mixture of Programming Languages
* Backed by Purpose-built Databases
* Containers & Functions

Here's the network, each services is represented by a dot. And every line is an enforced network rule that allows communication between two services, and coloured by team:

![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)

2. Data
* Purpose-built Databases
* Data Warehouse
* Data Lake

For System Availability & minimize the **"blast radius"** of any failures, design techniques:
1. Cell-based architecture
2. Sharding
3. Availability Zones
4. Regions

# Cloud Platform
1. Compute
* Cost Effective Scheduler 
    * Automatic scaling up and down to zero
    * Automatic Repairs
2. Databases - Purpose-built
* Data Model
* Query Patterns
   * In-Memory
   * NoSQL
   * SQL
   * Graph
3. Storage
4. Operational excellence
* Service Level Indicators (SLIs) & Service Level Objectives (SLOs)
* Metrics, Events, Traces & Logs
5. Security
* Network connectivity between workloads.
* Network security policy enforcement between workloads.

