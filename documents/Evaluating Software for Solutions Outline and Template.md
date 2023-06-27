# Evaluating Software for Solutions Outline and Template

## Process

1. Classify the solution
2. Define your selection criteria
3. Conduct walkthroughs (not demos) to showcase each selection criteria
4. Rank each solutions ability to deliver to the criteria
5. Use the mathematical score to inform your decisions

### Classifying the Solution

Putting every request through a full review would be cumbersome, inefficient and annoying for everyone involved, unless your organization has such tight spending controls that you need to do this. The first question to answer is: _"How much risk does this solution pose to my organization?"_

Much like any other risk matrix, there is a simple outline for this to make quick decision about the rigor needed. This template will suggest some ideas, but you will need to determine how you want to handle the levels of risk and how you will determine those levels.

I suggest considering these factors: 

* **Scope** - The number of your users that will be impacted
* **Data Classification** - The type of information this solution will hold/interact with, and therefore the controls that are required
* **Cost** - Setting a limit at which you will conduct a full or partial review

|	|	**SCOPE**	|	|	|
| ----- | ----- | ----- | ----- |
|	**Classification**	|	_Enterprise-Wide_	|	_Cross-Department_	|	_Single Team/Individual_	| 
|	_Protected_	|	Full Review	|	Full Review	|	Full Review	|
|	_Confidential_	|	Full Review	|	Full Review	|	Partial Review	| 
|	_Internal_	|	Full Review	|	Partial Review	|	Cursory Review	|
|	_Public_	|	Partial Review	|	Cursory Review	|	Cursory Review	|

#### Defining the Factors

##### Scope

* _Enterprise-Wide_ - Solution will be used by more than two divisions or more than 40% of the organization.
* _Cross-Department_ - Solution will be used by multiple departments in a single division or across divisions.
* _Single Team/Individual_ - Solution will be used by a single team, typically less than 5 people, or a single individual.

##### Classification

These are common terms used in corporate information security, but for reference they tend to mean:
* _Protected_ - This type of information is typically customer data; the type of information that, if leaked out, would seriously damage your organization or your customers.
* _Confidential_ - This type of information typically includes all trade secrets, company confidential information and employee data, including personally identifiable information.
* _Internal_ - This information would include basic process documents or guides; information that is internal to your organization vut would not be damaging if it were leaked.
* _Public_ - Information readily available to the public.

##### Cost

Each organization must define its own levels, but I recommend the following, and would adjsut based on your total revenue or G&A spend:
* _Large Solution_ - Any solution that incurs more than $25,000/yr in recurring costs or more than $40,000 in one-time cost.
* _Medium Solution_ - Any solution that incurs between $5,000/year and $25,000/yr in recurring costs, or less than $40,000 in one-time cost. 
* _Small Solution_ - Any solution that incurs less than $5,000/year in recurring costs, or less than $15,000 in one-time cost.


### Review Matrix and Details

|	Requirement	|	Cursory Review	|	Partial Review	|	Full Review	|
| ---------- | ---------- | ---------- | ---------- |
|	Cost Trigger	|	less than $5,000/year in recurring costs, or less than $15,000 in one-time cost	|	between $5,000/year and $25,000/yr in recurring costs, or less than $40,000 in one-time cost	|	more than $25,000/yr in recurring costs or more than $40,000 in one-time cost	|
|	Scope Trigger	|	used by a single team, typically less than 5 people, or a single individual	|	Solution will be used by multiple departments in a single division or across divisions	|	used by more than two divisions or more than 40% of the organization	|
|	Data Classification Trigger	|	Public, Internal	|	Public, Internal, Confidential	|	Protected, Confidential	|
|	Outline of Process	|	Produce a use case, receive budget approval, proceed with procurement review	|	Submit selection critiera, receive budget approval, proceed with procurement review	|	Selection criteria will be collected before a budget number is defined; budget approval must be granted before procurement review	|
|	Functional Review	|	List a reasonable use case and include it in your request. Any current solutions that match this use case will be recommended for review.	|	Using our defined template, present the criteria you used to evaluate and the results of yoru evaluation upon submission. Any current solutions that match supplied criteria that were not considered will be reviewed before proceeding with procurement. Any unmet security criteria will be re-reviewed.	|	Using our defined template, IT will work with stakeholders to define selection criteria, evaluate agaisnt our existing solutions and conduct reviews of new tools with stakeholders	|
|	IT-led review must occur?	|	No	|	No	|	Yes	|
|	Single Sign On	|	Social Preferred, SAML Accepted	|	SAML Preferred, Social Accepted	|	SAML Required	|
|	Auto-provisioning	|	not required	|	Auto-provisioning Preferred	|	Auto-provisioning Required	|
|	Solution Security	|	Auth Logs	|	Auth logs, Restrict data integrations	|	Auth logs, Restrict data integrations 	|
|	Location of Data	|	any non-sanctioned country	|	Country	|	Country	|
|	Compliance	|	SOC 2/ISO 27001	|	SOC 2/ISO 27001	|	SOC 2/ISO 27001, GDPR, Security Questionnaire	|
|	Licenses Required by Information Security	|	1	|	2	|	3	|
|	Solution Budget Will be Owned By	|	Director/VP of Requesting Team	|	Exec of Requesting Team	|	IT G&A	|

**SUGGESTIONS**

* Evaluate 2-3 external solutions, even if your internal solution is ranked highly
* Require walkthroughts with solutions engineers, not standard demos/slides; make them show how it will meet your criteria
* send your criteria ahead of the walkthrough; your vendors will thank you!
* Make sure you have all license options outlined, and all of your key criteria are met
* If you have an existing contract, don't sign an MNDA; it may supercede your existing agreement
* Always conduct basic due diligence on software - subprocessors and vendors are common source of breaches and data leaks

#### Requirements Descriptions

* Cost Trigger - _Does your organization want to initiate a more rigorous review for larger purchases?_
* Scope Trigger - _Do you want a more rigorous process if the solution will be used by most of the organization?_
* Data Classification Trigger - _Do you want a more rigorous process if the solution will interact with classified information?_
* Outline of Process - _A general outline of your process, high level._
* Functional Review - _Who will do the review, and what will they provide?_ 
* IT-led review must occur - _Do you want to require a specific team to do a more rigorous review?_
* Single Sign On - _Single Sign On is a great way to control access to systems while making it easier for authorized people to access a system._
* Auto-provisioning requirement - _If enough users will be in the system, auto-provisioning can save time for teams and IT to manage users._
* Security Requirement - _Any specific security requirements you may have._
* Solution Budget Will be Owned By - _If you want certain "sizes" of solutions to be owned by IT or some specific Business Apps team, this is a good place to define that team._

### Selection Criteria

Suggested Groupings
* Dealbreakers
* Security
* Global Features

Suggested Levels of Importance
* Need - Prevents Work
* Want - Reduces Annoyance/Increases Efficiency

Suggested Scoring Metrics
* 9 - Meets this criteria well
* 3 - Somewhat meets this critera
* 1 - This criteria can be met with an add-on
* 0 - Does not meet this criteria

Suggested Calculations for Ranking
* Dealbreakers - if any of these are not met, the solution is disqualified
* Need Criteria - 3
* Want Criteria - 1
* Group the criteria by category or area of work, e.g. "Billing", "Invoicing", "Customer Support", "Lead Generation", "Sales"
