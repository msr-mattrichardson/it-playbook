# Data Dictionary Template

## What are the benefits of a data dictionary?

* Helps to understand the overall database design, structure, relationships, and data flow
* Facilitates building a common vocabulary and hence shared understanding amongst data users
* Helps detect errors and anomalies in data
* Enables crowdsourcing data quality and data integrity checks
* Helps save time on data discovery and enables reliable analytics and reporting
* Assists in managing data quality, consistency, and security for compliance audits
* Helps enforce database management and programming standards
* Makes it easier to onboard new analysts/data engineers into the team

### Risks to mitigate with data dictionaries

* information can become stale if not part of changes
* lack of functional details regarding data
* diagrams are not always visually appealing
* can be difficult for nontechnical users to understand

### How do I maintain this dictionary and ensure it is useful?

Incorporating your data dictionary as part of your change process and definition of done can be useful to ensure the document is actively used and updated.

## Data Dictionary Outline

* **Division & Department** - Organizational structures within your organization.
* **Term** - The name of the "term" or "data asset" that will be used across the organization.
* **Term Owner** - The name of an individual who "owns" the term/data asset; this is the only person who has the authority to make changes to this item.
* **Definition** - A narrative definition of the term. Including use cases can be helpful.
* **Data Source of Truth** - The location/system where this term/asset is, that serves as the "source of truth" for all other references.
* **How to Calculate** - Define how this term/asset is calculated.

### Data Dictionary Term Definitions

|  Division  |  Department  |  Term  |  Term Owner  |  Type of Data Asset  |  Definition  |  Data Security Classification  |  Data Source of Truth  |  How to Calculate  |
|  -----  |  --------  |  --------  |  --------  |  --------  |  ----------------  |  --------  |  --------  |  ----------------  |
|  Division1  |  Department1  |  DataTerm1  |  DataOwner1  |  AssetType1  |  Definition1  |  Protected  |  Truth1  |  Calculate1  |
|  Division1  |  Department1  |  DataTerm1  |  DataOwner2  |  AssetType1  |  Definition2  |  Confidential  |  Truth2  |  Calculate2  |

#### Other Potential Dictionary Items

* **Field Definitions** - defining data components and whether they are required or not
* **Compliance Alignment Table** - which data elements are applicable to specific compliance requirements
* **Data Attributes** - Table of all data elements, where they are and what type of field they are
* **Acceptable Value List** - A list of all acceptable values for picklist items
