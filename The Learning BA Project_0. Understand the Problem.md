# 0. Understand the Problem
> [[0.1. README_The Learning BA Project]]

**Created:** 2026-09-29
**Done:** 2026-10-01

## My Purpose to Study BA Method

- BA skills is good for me to do other things I want to do. It helps make my ideas digestible to other people , which is essential for me to do other things like later on I want to make my own business, or becomes a product owners. 
	- ==Strong BA skills are really about **communicating ideas clearly**==: clear enough that everyone can understand it, agree on it, and turn it into something real.
	- That skill is useful almost everywhere: 
		- when presenting your own ideas in product roles.
		- even when you’re explaining plans at home.
## Define BA Method and Business Analysis
- ==**BA Method** is a systematic, structured, and orderly way or procedure to conduct business analysis.==

## BABOK vs Karl's Software Requirement

### Babok BA Definition
- business analysis is the practice of ==enabling change== in an ==organization== by ==defining needs== and ==recommending solutions== that ==deliver value== to ==stakeholders==
- BA core concepts (6):
	1. Change = Def.Change => the act of transformation
	2. Need = Def.Need => a problem or opportunity need to be addressed
	3. Solution = Def. Solution => a specific way of satisfying one or more needs in a context
	4. Stakeholder = Def. Stakholder => a group or individual with a relationship to the change, need or solution
	5. Value = Def. Value => the worth, importance or usefulness of something to a stakeholder within a context
	6. Context = Def.Organization => the circumstances that provide the understanding of the change
- BA Knowledge areas:
	- ==3 areas follow the change itself (the main flow)==
		1. Strategy Analysis
		2. Requirement Analysis and Design Definition
		3. Solution Evaluation
	- ==3 areas support the work the whole time==
		1. BA planing and Monitoring
		2. Elicitation and Collaboration
		3. Requirement Life Cycle Management

### 0. Overall Purpose
- **BABOK:** business analysis means ==enabling change== in an ==organization== by ==defining needs== and ==recommending solutions== that ==deliver value== to ==stakeholders==.
- **Wiegers:** requirements engineering makes sure the **right product is understood, specified, built, and validated**.
- **Software Requirement Joggers** : Chap 1
- **Practical:** BABOK is broader — it covers business change, value, requirements, and solution evaluation. Wiegers is narrower — he focuses on software requirements.

### 1. Strategy Analysis
**Question:** What is the need, and is the change worth it?

- **BABOK:** understand the current state, define the future state, assess risks, and justify the change.
- **Wiegers:** start with business requirements — objectives, problems, opportunities, and scope. Prioritize by value, cost, and risk.
- **Software Requirement Joggers** : Chap 8.
- **Practical:** understand the problem and goal before choosing a solution; check that the benefits are worth the cost.
- **Chapters:** Ch. 5 _Establishing the business requirements_

### 2. Requirement Analysis and Design Definition
**Question:** What exactly should the solution be?

- **BABOK:** specify and model requirements, verify them, define design options, and recommend a solution.
- **Wiegers:** analyze, specify, and validate requirements. Separate business, user, functional, and nonfunctional requirements.
-  **Software Requirement Joggers** : Chap 4,5
- **Practical:** turn business needs into clear requirements; make them detailed enough for the team to build.
- **Chapters:** Ch. 8, 9, 10, 11, 12, 13, 14, 17

### 3. Solution Evaluation
**Question:** Did the solution deliver the value?

- **BABOK:** measure how the solution performs, find what limits its value, and recommend improvements.
- **Wiegers:** no separate area — closest topics are validating requirements, success metrics, and evaluating existing or packaged solutions.
-  **Software Requirement Joggers** : Chap 6. 
- **Practical:** set success metrics early; check them after release; if value is low, find the cause (the solution or the organization); recommend fixes or next steps.
- **Chapters:** Ch. 5, 17, 21, 22

### 4. BA Planning and Monitoring
**Question:** How will I organize and improve my own BA work?

- **BABOK:** plan the BA approach, stakeholder engagement, governance, and information management. Improve BA performance over time.
- **Wiegers:** spread across several chapters — good practices, the BA role, planning, risk, and process improvement.
- **Software Requirement Joggers** : Chap 2
- **Practical:** plan how you will do BA work; agree on who approves requirements and changes; review and improve your process regularly.
- **Chapters:** Ch. 3, 4, 19, 23, 31, 32

### 5. Elicitation and Collaboration
**Question:** How do I get information from people and keep them aligned?

- **BABOK:** prepare, conduct, and confirm elicitation. Share information and manage stakeholder collaboration.
- **Wiegers:** a core activity — find the right users and use techniques like interviews, workshops, observation, and prototypes. Build a partnership with customers.
- **Software Requirement Joggers** : Chap 3
- **Practical:** talk to the right people; choose the right technique; confirm what you heard; keep stakeholders informed.
- **Chapters:** Ch. 2, 6, 7, 15

### 6. Requirement Life Cycle Management
**Question:** How do I keep requirements organized as they change: tracing, prioritizing, approving?

- **BABOK:** trace, maintain, prioritize, assess changes, and approve requirements.
- **Wiegers:** called requirements management — covers baselines, versions, status, change control, traceability, prioritization, reuse, and tools.
- **Software Requirement Joggers** : Chap 7. 
- **Practical:** baseline what is agreed; check the impact before accepting changes; link requirements to goals and tests; re-prioritize as needed.
- **Chapters:** Ch. 16, 18, 27, 28, 29, 30

### User Stories, Acceptance Criteria, and Models
- **BABOK:** allows requirements in many forms and levels of detail. Models are part of Requirements Analysis and Design Definition.
- **Wiegers:** covers use cases and user stories, analysis models, and acceptance tests.
- **Practical:** these are **techniques and formats**, not the definition of BA work.
- **Chapters:** Ch. 8, 12, 17

## Summary
### A BA Method Is Usually Built From Four Layers
**1. Overall process (the big picture).** 
- in  BABOK organizes it into six _knowledge areas_:
	- Business analysis planning and monitoring
	- Elicitation and collaboration
	- Requirements life cycle management (including change and traceability)
	- Strategy analysis (the problem, current vs. future state)
	- Requirements analysis and design definition
	- Solution evaluation
- Wiegers splits it more simply: **requirements development** (elicit → analyze → specify → validate) and **requirements management** (changes, versions, traceability).
**2. Tasks (what you do in specific situations).** 
- For example: handle a change request, run an elicitation session, prioritize requirements, or get sign-off. 
**3. Techniques (tools you choose from).** 
- Interviews, workshops, user stories, acceptance criteria, process flows, decision tables, mockups, and so on. 
- BABOK lists about 50. You pick the right ones for each task.
**4. Outputs (what you produce).** 
- Problem statement, FR, user stories and AC, models, change log, sign-off.

Eg: For interviews, a simple way to show you understand this: _"I follow a structured process: understand the problem, elicit, analyze, specify, validate, and manage changes. For each step I choose techniques that fit the project. For example, for a change request I do an impact analysis, update the FR and AC, and get sign-off."_ That shows the process, a task, and techniques in a few sentences.

## Fun Facts
### Polya "How to Solve It" Relates to BA Tasks
- four steps map onto BA work almost directly. 
- **The main difference** is that Polya assumes the problem is **given and well-defined**

| Polya                         | BA equivalent                                    | Polya's key question → BA version                                                                                                           |
| ----------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Understand the problem** | Identify the problem, define scope, elicit       | "What is the unknown? What are the data and conditions?" → What does the client _really_ need? What are the constraints and business rules? |
| **2. Devise a plan**          | Analyze, root cause, choose approach             | "Have you seen a similar problem before?" → Is this like a feature or change request we've handled? Can I reuse a pattern?                  |
| **3. Carry out the plan**     | Write FR/AC, build mockups, specify the solution | "Check each step." → Is each requirement clear, testable, and consistent?                                                                   |
| **4. Look back**              | Validate, UAT, lessons learned                   | "Can you check the result? Can you use it for another problem?" → Does it solve the original problem? What would I do differently?          |
**The main difference** is that Polya assumes the problem is **given and well-defined**. In BA work:

- **The problem is often unclear or wrong.** The client asks for a feature, but the real need is something else. So step 1 takes much more effort.
- **People are part of the problem.** Stakeholders disagree, change their minds, or don't know what they want. You have to negotiate, not just reason.
- **The "answer" isn't simply right or wrong.** It's a trade-off between time, cost, and value, and it has to be agreed on.
- **It loops.** Requirements change, so you cycle through the steps many times instead of once.

--------
## Oldies
### My First Attempt at Defining Business Analyst
Business analyst's role is to evaluate and enable changes in an organization: 
- **Find the need:** Why is a change needed at all? 
- **Analyze the value:** Is this change worth making? 
- **Shape the solution:** What exactly should be built? (user stories, AC, models) 
- **Check the value:** Did the change actually deliver what we expected? 
- **Work with stakeholders throughout:** with the business stakeholders to understand the need and confirm the value, and the delivery team ( eg: devs, testers) to shape a solution that works.

### My First Attempt at Harmonizing My Own Understanding with BABOK and Karl Wiegers

|Your BA role|BABOK® Guide|Karl Wiegers — _Software Requirements_ / requirements engineering|Practical interpretation|
|---|---|---|---|
|**1. Find the need: Why is a change needed?**|**Strategy Analysis** — analyze the current state, define the future state, assess risks, and identify/justify change|**Business requirements** — understand the business objectives, problems, opportunities, and desired outcomes that motivate the project|Understand the **problem/opportunity and business goal before jumping to a solution**|
|**2. Analyze the value: Is this change worth making?**|**Strategy Analysis** includes assessing potential value, risks, and feasibility of the change; **Solution Evaluation** later assesses actual value|Requirements engineering starts with understanding **business objectives and project scope**; Wiegers emphasizes prioritizing requirements according to business value, cost, risk, etc.|Establish whether the expected benefits justify the investment|
|**3. Shape the solution: What exactly should be built?**|**Requirements Analysis and Design Definition** — specify/model requirements, verify requirements, define design options, and recommend a solution|Strong emphasis on **requirements elicitation, analysis, specification, validation, and management**; distinguishes business, user, and functional/nonfunctional requirements|Turn business needs into requirements that the delivery team can actually implement|
|**User stories, acceptance criteria, models**|BABOK supports requirements in different forms and levels of abstraction; models are explicitly part of Requirements Analysis and Design Definition|Wiegers discusses use cases, scenarios, functional requirements, quality attributes, prototypes, etc.; user stories are more associated with Agile approaches than specifically with Wiegers|These are **techniques/formats**, rather than the definition of BA work itself|
|**4. Check the value: Did the change deliver what we expected?**|**Solution Evaluation** — measure solution performance, analyze measures, evaluate limitations, recommend actions|Requirements validation/verification focuses strongly on whether requirements and delivered software meet needs; post-release evaluation is also relevant, but Wiegers' framework is more requirements-centric than BABOK's explicit Solution Evaluation domain|Compare **actual outcomes with expected business value**, not merely “did we build the requirements?”|
|**5. Work with stakeholders throughout**|**Stakeholder Engagement**is a core BABOK concept and is integrated throughout all knowledge areas|Wiegers emphasizes stakeholder involvement in elicitation, analysis, specification, validation, and requirements management|BA is a **bridge/facilitator**, continuously aligning business stakeholders and the delivery team|
|**Overall purpose**|BA enables **change by defining needs and recommending solutions that deliver value**|Requirements engineering ensures the **right product is understood, specified, built, and validated**|BABOK is broader: **business change + value + requirements + solution evaluation**. Wiegers is more focused on **software/product requirements engineering**|
