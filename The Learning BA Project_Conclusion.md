# The Learning BA Project's Conclusion
>  [0.1. README_The Learning BA Project](<0.1. README_The Learning BA Project.md>)
>  

# 1. Overview of software requirements

## Intro
- Software requirements are the necessary and sufficient properties of the software must have to meet user's needs
- There are many types of software applications, depending on their purpose: ranging from business software to system software
- Systems are composed of subsystems. Subsystems are composed of hardware, software, people, and the interface among these 3 components.
![[Screenshot 2026-10-08 at 10.20.24.png]]

## Why should i define requirements
- coz the cost to cover for requirements defect is super high: cost overruns, expensive rework, poor quality, late and every one dissatisfied and exhausted

# Requirements verification and validation
- During requirement development, **conceptual test** is necessary to help uncover incomplete, incorrect and unclear requirements.
- After code is written, **user acceptance test** ensures the software is correct ( per previously BA confirmed specs) 
- As requirements is developed, **they are verified** to ensure that they satisfied the specifications of the requirements development activity (BA confirm with user if their understanding of the requirements truly satisfy user's need)
- ![[Pasted image 20261008103517.png]]

# What types of requirements are there?
- functional and nonfunctional
- functional are the doing part of the software: actions, tasks, software behaviors
- non function are the being part of the software: quality atrributes( eg: performance), design and implementation constraints, and external interfaces(hardware, software, human)

# Where do requirements come from?
![[Screenshot 2026-10-08 at 10.39.47.png]]
- **business requirements** include vision(how users gonna use this for) + scope ( what are all the features or capability of the software). 
- **user requirements per feature** are expressed in terms of models. 
- **software requirements per user requirement:** details description of functional and non functional requirements 
# ==How should I document my requirements==
- Textual outline
![[Pasted image 20261008104748.png]]
- Tree Diagram
![[Pasted image 20261008104811.png]]
- Models
![[Pasted image 20261008104825.png]]

# ==Good requirement documentation practices==
- Business requirement = textual statements of vision. Then, supplement product scope = 1 or more diagrams.
- User requirements = variety of models. Things are made more interesting and also reveal missing and erroneous requirements. 
- Supplement outline forms of text software requirements with user requirements models

# ==🟡 What are characteristics of excellent requirements?==
1. **correct:** represents real needs 
2. **complete:** include all needed elements (functionality, external interfaces, quality attributes, and design constraints)
3. **clear:** can be understood in the same way by all stakeholder
4. **concise:** stated simply in the minimal way possible. 
5. **consistent:** do not conflict with other requirements
6. **relevant:** necessary to meed to business objective. 
7. **feasible:** possible to implement. 
8. **verifiable:** there is a finite, cost effective technique to determine is satisfied. 

# ==Key practices that promote excellent requirements== 
- clear vision of end product
- well-defined and shared understanding of the project scope
- involve stakeholders throughout the requirements process
- represent and discover requirements using multiple models
- document the requirements clearly and consistently
- continually validate the requirements are the right one to focus on
- verify the quality of the requirements early and frequently
- prioritize the requirements and remove unnecessary ones.
- establish a baseline for requirements of the reviewed and agreed-upon requirements that will serve as a basis for further development.
- trace the requirements's origins and how they link to other requirement and system elements
- anticipate and manage any requirements change

# What is requirements engineering?
- is comprised of requirements development (elicit, analyze, specify, validate) and requirements management (establish baseline, control change, trace requirements) 
![[Pasted image 20261008134925.png]]

# ==Why is it important to let requirements evolve?==
- accelerates requirements understanding while producing them as thoroughly as possible by develop iterative manner. ==To develop requirements iteratively:==
	- elicitation technique that allow customers to requirements as early as possible
	- develop requirements using multiple short cycles or iterations (elicit, analysis, specification and validation)
	- conduct short requirement rero at the end of each requirements iteration to learn and improve. 

# Who is involved?
- many stakeholders in numerous roles. 
![[Screenshot 2026-10-08 at 14.20.33.png]]
- business and software managers need to ensure that the team develops excellent requirements and manages them appropriately. 

# 2. Setting the Stage for Requirements Development

## ==What tools and techniques will I use to set the stage?==
- define the product vision = a vision statement
- clarify terms = a glossary
- identify requirements risks = a requirements risk mitigation strategy. 
### 2.1 Vision Statement
![[Pasted image 20261008143236.png]]
### 2.1.1. Variations
![[Pasted image 20261008143422.png]]
### ==2.2 Glossary
- **TO: establish a common vocabulary for key business terms and to help team reach a mutual understanding.** 
- What do the terms and business concepts that we use mean?
- find the person can best identify a starting list of terms
- identify the important terms. 
- draft definitions, then get other people to review. 
- this glossary will evolve as team iterates through requirements.
![[Pasted image 20261008144603.png]]

- Terms in the glossary will appear in: 
	- relationship maps and process maps
	- context diagrams
	- data models
	- states in state diagrams
	- use case name and use case steps
	- business rules. 
### 2.3 Requirements risk mitigation strategy
- to assesses requirements-related risks and identifies actions. 

# 3. Elicit the Requirements
- = identify sources and evokes requirements from those source

## How do I elicit software requirements?
![[Pasted image 20261008153512.png]]

# What tools and techniques will I use to elicit requirements? 
![[Pasted image 20261008153724.png]]

## 3.1. Requirements Source List
- inventory of people, specific documents, and external information sources that you will elicit requirements from.  
- **TO:** 
	- ==**identifies sources**
	- ==**facilitates planning for efficiently involving stake-holders.** 

## 3.2 Stakeholder Categories
- categories of people who have vested interest in the software product: 
	- customers(sponsor, product champion)
	- users (direct users, indirect users)
	- other(advisors, providers)
- **TO:**
	- ==**to understand stakeholders**
![[Screenshot 2026-10-08 at 16.11.52.png]]


# 3.3 Stakeholder Profiles
- ==**to understand the interests, concerns, and product success criteria of stakeholders**
- ==**educate team about stakeholder expectations.**  
![[Screenshot 2026-10-08 at 16.18.33.png]]

