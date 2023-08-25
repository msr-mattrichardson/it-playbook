# Systems Ownership and Digital Asset Inventory Template

Determining what information assets exist in the organization and who is responsible for what is a critical part of protecting information assets. This document is intended to provide a set of terms and their descriptons that you can use to

* Track your digital assets
* Classify the risk of those assets accurately
* Improve the administration of those assets
* Assist with good cahnge management and reduce the liklihood of events/incidents related to operational changes
* Encourage good continuous improvement practices
* Remain compliant with operational best practices and audit standards

## Data to track for information/digital assets

* Application or Digital Asset Name
* Functional Description
  * _Describe what this asset does, not waht it is e.g. houses data, workflows and automation that enable our salesforce and enforce our accepted process flows._
* Key Processes this software supports
  * _Listing or linking to the key processes an application supports can help with good change management and improve the synergy between technology and process._
* Data Classification
  * _Based on your organization's policies, what is the classification of data this system will house/interact with? I recommend classifying it based on the most risky type of data the system will interact with._
* Status
  * _types of statuses could include Still In Use, Not Available for Use, Decommissioned_
* Deployed As
  * _Is this a SaaS app, a PaaS app, a Desktop app, a Mobile app, etc._
* Role-based access
  * _Define the parameters you will use to provide people access to the system; I would not recommend defining the authorization level they have here._
* System Owner (role/person)
  * _The system owner is the person/role responsible for all aspects of a digital asset: performance, alignment to budget, security, data integrity, configuration. The System Owner is the authority of a system and will be asked to approve all cahnges, integration and the continued use of a system._
* Budget Owner
  * _This is the person who can approve increases in spend for this application that are not within budget._
* Data Custodian
  * _This term is primarily used in relation to GDPR compliance and information security compliance (ISO, SOC, SSAE). The Data Custodian stewards the data within the system, ensuring the accuracy of information and handling any data requests._
* System Administrator
  * _This person/role, of which there may be multiple, handles the regular maintenance, configuration and executes approved changes within a system. Generally, this is a technical resource or specific subject matter expert._
* Security administrator
  * _This person/role is the individual who can approve changes to the security settings of an application. A person with this responsiblity can override the System Owner as it relates to security-impacting changes._
* Support / Help Channel
  * _How will users and administrators ask for help? Indicate how people should get answers to their questions, and how they request assistance._
* Support License Level
  * _Defien any specific support plan we have._
* Allowed Authentication Methods
  * _Stanfdard, Single Sign On - SAML, Social Sign Ons, OAuth, API Token, Passwordless, etc._
* Supports SAML?
  * _A yes/no response, typically used to identify applications in your ecosystem that could go behind your Single Sign On Provider such as AzureAD, Okta, Jumpcloud, Ping, etc._
* Is Multifactor Authentication enforceable?
  * _Outside of enforcing SAML authentication, does this system allow the enforcement of multifactor authentication?_
* Provisionioning Method
  * _How are users able to be added into the system: manually, just in time, SCIM?_
* Provisioning team
  * _Define the team responsible for adding users in and removing them._
* Supports Auto-provisioning
  * _A yes/no response, typically used to identify applications that can use automatic methods to administer user access and/or authorization levels._
* System Backlog
  * _The location wher eyou will keep a list of suggested improvements to this system. It can be helpful to have a backlog that connects a system with the key processes it supports._
* User Guide
  * _A link to the guide or location where users can get answers to questions._
* Admin Guide
  * _A link to the guide or location where system administrators can get answers to questions._
* Last Contract Renewal Date
* Next Contract Renewal Date
* Last security review Date
* Minimum notice to terminate contract
* License Type
* License Comments
* Integrates with these systems
  * _List out the systems that this asset will integrate with. This helps with change management and security monitoring._
* Vendor Contact Name
* Vendor Contact Email


