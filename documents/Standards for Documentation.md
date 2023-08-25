# Standards for Documenting Technology and Processes

### Overview

Knowledge is power, and with great power comes the great responsibility to ensure that knowledge is accurate and used for good! One of the challenges for any organization, especially that is growing/scaling is we find our teams in a regular shift between Storming/Forming/Norming as the organization changes and we strive to achieve a state of Performing. Simple, effective knowledge management is incredibly useful to navigate these shifts and provide good stewardship of processes and systems.

This document outlines some suggestions for a simple standard for documenting system and process information that remains actionable and usable throughout any stage of a company's operational maturity.

**Suggested Hierarchy of Documentation**

* Policies
  * Processes
    * Procedures
      * System User Guides (may contain procedures)
      * Guidelines
* Standards (can be referenced anywhere)

### Intended Audience

Anyone who uses a system or process, or is responsible for the succesful operation of those systems or processes.

## Systems Documentation

Systems documentation can be challenging to maintina, so it is important to keep these documents simple and useful on a regular basis. These documents can contain information, procedures and other useful reference material. Typically, USer gduies (the official copy) live on a company knowledge center / intranet. Admin guides and technical Good systems documentation have a number of benefits.

**BENEFITS OF GOOD SYSTEMS DOCUMENTATION**

* Defines standard operating procedures to reduce the need for regular approvals (when a process is pre-approved for changes)
* Sets the stage for good controls and compliance
* Reduces problems/incidents from changes
* Reduce requests for help by providing good user documentation
* Provide a usable reference for administrative tasks that are not done regularly (no need to remember how to do something every 6 months)

#### Examples of Systems that Benefit from Admin/User Guides

* Support/Ticketing
* Identity and Access Management
* CRMs
* ERP/Financial
* Infrastructure as a Service / Cloud Service Providers
* Code Repositories

### System Documentation

Administrative documentation should be used actively as part of your continuous improvement cycles, troubleshooting efforts and change reviews.

|  Type of Document  |  Examples of this type of document  |  Details to include  |  When to Update  |  Who is responsible for updating  |  Visibliity  |  Reference this document in  |
|  -------  |  ------------  |  ------------  |  --------  |  --------  |  --------  |  --------  |
|  Technical Diagram  |  ERD (Entity Relationship Diagram), Data Flow, System Architecture, System Integration  |  The primary system, important structural information, important data integrations |  After any pre-approved or reviewd change; make part of "definition of done"  |  System Owner & Administrator(s) - Level 2/3  |  All technical staff across the company  |  System Admin Guides  |
|  Document  |  (Administrative Guide)(./Admin%20Guide%20Template.md)  |  Context for the system, Useful technical information, IAM processes, procedures, FAQs   |  Reference for all administrative actions; update ongoing  |  System Owners and Administrators  |  System Owners and Administrators  |  Process Documents, System Inventory  |
|  Document  |  (User Guide)(./USer%20Guide%20Template.md)  |  Context for the system: why we use it, How to Use the system (proceudres), FAQs   |  Update when a system change or process change is made that impacts the system, update as part of support tickets  |  System Owners, System Administrators, Process Owners, Trainers  |  All users  |  Process Documents, System Inventory  |

## Policies and Standards

Policies and standards set the foundation for your practices and governance. These documents should inform how you do things, and be as lightweight as they can for as long as they can. Good governance policies enable teams, set clearly defined and useful boundaries, set clear expectations of what to do and not to do and help set the stage for future potential compliance efforts (e.g. SOC, ISO, GDPR, SSAE).

**BENEFITS OF GOOD POLICY AND STANDARDS DOCUMENTATION**

* Helps reduce company risk
* Provides requirements that align entire teams / the company to common practices
* Sets the stage for future compliance
* Provides clear expectations and enforceable rules 

#### Examples of Policy and Standards Documentation

* Security Policy
* Change Management Policy
* Travel Policy
* Infrastructure Standards
* System Security Baselines
* Product Management Guidelines

### Policy and Standards Documentation

Policy and standards documentation sets the defining parameters for what behaviors are enouraged and which behaviours are against the rules.

|  Type of Document  |  Used For  |  Examples of this type of document  |  When to Update  |  Who is responsible for updating  |  Visibliity  |  Reference this document in  |
|  -------  |  ----------  |  ------------  |  ------------  |  --------  |  --------  |  --------  |
|  Policy  |  Defining the rules which you use to govern your systems and processes; these are enforcable and not following them can result in consequences to the business/team/individual  |  (Policy template)(./Policy%20Template.md), SDLC, Security Policy, Vacation Policy, Travel Policy, Expense Policy  |  After any pre-approved or reviewd change; make part of "definition of done"  |  System Owner & Administrator(s) - Level 2/3  |  All technical staff across the company  |  Standalone, other Policies, Standards, Process Documents  |
|  Standard  |  Defining a common set of standards or practices you will follow; may be enforceable if reference in a policy.  |  (Standards Definition Template Guide)(./Process%20or%20Standards%20Definition%20Template.md), System Standards, Security baselines  |  Update as needed, typically following a major change or change in architecture/key processes  |  System Owners or Process Owner, Sr. Management Team  |  Everyone (unless standards expose sensitive information)  |  Standalone or in Policies  |
|  Guidelines  |  Recommended steps to follow or a general philosophical idea; not enforceable but serves to shape conversations.  |  Product philosophy, managerial resources, customer conversation guidelines   |  As needed  |  Varies  |  Varies, but usually a team  |  Standalone; do not inclue in policies or standards  |

## Process Documentation

Process documentation is incredibly useful to teams and individuals. A process document is the "source of truth" for a key business process: a set of steps that should follow a given path and procedures. A "Key Business Process" is any process that, if it is not successfully executed according to the outlined method in the documentation, will put your team or organization at signficant risk.

**BENEFITS OF GOOD PROCESS DOCUMENTATION**

* SImplifies training by having a "source of truth" for how the process should work
* Reduces confusion for the team; they can alwasy refer to the process document as a the source of truth
* Helps inform the efficient and effective configuration of systems/tools that support this process
* Helps continuous improvement efforts

#### Examples of Key Business Processes

* New Sales
* Renewals
* Customer Success / Lifecycle
* Procurement
* Contract Reviews
* Vendor Management
* Secure Software Development Lifecycle
* Identity and Access Management
* System Change Management

### Process Documentation

Process documentation should be a part of every continuous improvement and performance disucssion related to processes. These documents also aid greatly in systems design, requirements gathering and change management for processes and systems.

|  Type of Document  |  Examples of this type of document  |  Details to include  |  When to Update  |  Who is responsible for updating  |  Visibliity  |  Reference this document in  |
|  -------  |  ------------  |  ------------  |  --------  |  --------  |  --------  |  --------  |
|  Process Flow Diagram  |  Process Flow, Swim Lanes, Data Flow  |  High level steps, important decision points, key team/stakeholder handoffs, needed inputs and desired outputs |  Any time the process is changed or a supportive system is changed that will affect the process  |  Process Owner  |  All users  |  Process Documents  |
|  Process Document  |  (Process Definition Template)(./Process%20or%20Standards%20Definition%20Template.md)  |  High level steps, change log, process flow diagram, referenes to procedures, desired outcome   |  Any time the process is changed  |  Process Owners  |  All users  |  Training, Admin Guides, User Guides  |
|  Procedures  |  (Process Definition Template)(./Process%20or%20Standards%20Definition%20Template.md), (Administrative Guide)(./Admin%20Guide%20Template.md), (User Guide)(./USer%20Guide%20Template.md)  |  Step-by-step instructions, visual references   |  When the process or the system is revised; anytime a process changes!  |  System Owners and Process Owners  |  All users  |  Process Documents, Admin Guides, User Guides  |
