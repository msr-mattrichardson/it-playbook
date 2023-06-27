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
|	_Confidential_	|	Full Review	|	|	| 
|	_Internal_	|	Full Review	|	|	|
|	_Public_	|	Full Review	|	|	|

#### Defining the Factors

**SCOPE**
* _Enterprise-Wide_ - Solution will be used by more than two divisions or more than 40% of the organization.
* _Cross-Department_ - Solution will be used by multiple departments in a singel division or across divisions.
* _Single Team/Individual_ - Solution will be used by a single team, typically less than 5 people, or a single individual.

**Classification**
These are common terms used in corporate information security, but for reference they tend to mean:
* _Protected_ - This type of information is typically customer data; the type of information that, if leaked out, would seriously damage your organization or your customers.
* _Confidential_ - This type of information typically includes all trade secrets, company confidential information and employee data, including personally identifiable information.
* _Internal_ - This information would include basic process documents or guides; information that is internal to your organization vut would not be damaging if it were leaked.
* _Public_ - Information readily available to the public.

**Cost**
Each organization must define its own levels, but I recommend the following, and would adjsut based on your total revenue or G&A spend:
* _Large Solution_ - Any solution that incurs more than $25,000/yr in recurring costs or more than $40,000 in one-time cost.
* _Medium Solution_ - Any solution that incurs between $5,000/year and $25,000/yr in recurring costs, or less than $40,000 in one-time cost. 
* _Small Solution_ - Any solution that incurs less than $5,000/year in recurring costs, or less than $15,000 in one-time cost.


#### Types of Reviews

##### Full Review

* Gather requirements and evaluate solutions before selecting a solution of a hard budget number
* Conduct a review of all relevant internal solutions against the selection criteria (do this again if you have already done it before; this can be a useful way to reduce tool overlap and identify specific gaps a new solution must address)
* Evaluate 2-3 external solutions, even if your internal solution is ranked highly; require walkthroughts with solutions engineers, not standard demos/slides (send your criteria ahead of the walkthrough: your vendors will thank you!)
* License should include security components (Single Sign On, SAML, Logs, Data Loss Settings)
* License should include automatic user provisioning (SCIM, Federation) to ease burden on IT/Security for deployment and user changes
* Perform standard due diligence on privacy policy, security settings, license agreement, terms of service, service agreement


##### Partial Review

* Gather key requirements and evaluate solutions before purchasing a solution
* Conduct a review of all relevant internal solutions against the selection criteria (do this again if you have already done it before; this can be a useful way to reduce tool overlap and identify specific gaps a new solution must address)
* Evaluate 1-2 external solutions, even if your internal solution is ranked highly; require walkthroughts with solutions engineers, not standard demos/slides (send your criteria ahead of the walkthrough: your vendors will thank you!)
* License should include security components (Single Sign On, SAML, Logs, Data Loss Settings)
* License would ideally include automatic user provisioning (SCIM, Federation) to ease burden on IT/Security for deployment and user changes
* Perform standard due diligence on privacy policy, security settings, license agreement, terms of service, service agreement

##### Cursory Review

Go through your standard process, and verify the privacy policy, usage agreement, terms of service, service agrement and basic functionality are met.

#### Enterprise-wide 

#### Cross-divisional

####

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
