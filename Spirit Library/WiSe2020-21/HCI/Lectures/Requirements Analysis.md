## Requirements Analysis
___
### What are Requirements?
> **Requirements describe what the problem is** whereas *design describes how the solution looks* and works

- What are requirements?

### Different Types of Requirements
> When thinking of requirements, remember to think of **who the users are** (how often they use the system, their capabilities, etc.), what their **usability goals** are, the **environment & context** in which they're using the system

- What types of requirements are there?
    - **Functional requirements** - what the system should do
    - **Non functional requirements** - constraints on the system, development process
    - **Data requirements** - what type of data, amount of data, where/how they will be stored, accuracy of data, persistency
    - **Environmental/Context of use requirements** (physical, social, organizational)
- What are user requirements?
	- Requirements that describe who the users are. Analysis of user requirements leads to user profiles
	- **Characteristics**
		- ability, background, education, attitude to computers, personal circumstances (e.g., single mom), personality
	- **Capabilities**
		- physical ability, size, strength, dexterity, disability, etc.
	- **System use**: novice, expert, casual, frequent
		- Novice: step-by-step (prompted), constrained, clear info
		- Expert: wants flexibility, access/power
		- Frequent: short cuts
		- Casual/infrequent: clear instructions, e.g., menu paths
- What are usability requirements?
	- Relate to the task and the users (e.g., learnability of system, effectiveness to complete task, safety/reduction of errors, memorability if system isn't used a lot, also fun and aesthetics - UX)
- 

### User Diversity (User Profiles, Personas, Stakeholders)
> User needs and preferences vary with age, gender, lifestyle, etc. (e.g., disability, pregnancy)
- Shneiderman's principle "Recognize User Diversity" (see: [[Shneiderman's 8 Golden Rules]])
	- Not every user is the same! Who are the people involved?
		-  decision makers?
		-  users?
		-  what relationships exist between users?
		-  what relationships exist between users and decision makers?
		-  what role do users have (customer, administrator, controller, supervisor, etc.)?
		-  which tasks are performed by the user (in the real world and in the system)?
		-  Why do people use a system and what is their motivation?
- Who are stakeholders?
	- **Anyone affected by success or failure of the system is a stakeholder**
		- primary: actually use system
		- secondary: receive output or provide input
		- tertiary: no direct involvement but affected by success or failure
		- facilitating: involved in development or deployment of system
	- those who interact directly with the product (end-users)
	- those who manage direct users
	- those who receive output from the product
	- those who make the purchasing decision
	- those who use competitor's products
- Example: Classifying stakeholders of an airline booking system
	- Primary
		- travel agency staff, airline booking staff
	- Secondary
		- customers, airline management
	- Tertiary
		- competitors, civil aviation authorities, customers' travelling companions, airline shareholders
	- Facilitating
		- design team, IT staff
> User profiles describe characteristics of types of users for a system, and personas capture a user profile for a key user type **inspired from actual data**
- What is a user profile?
	- a summary of relevant characteristics of the users that derive from the analysis of requirements and user needs
- Example of user profile for mobile phone users
	- ![[User Profile - Mobile Phone.png]]
- What is a persona?
	- A method that connects requirements with early design
	- Captures a set of user characteristics (user profile) for key user types (could include 'extreme users')
	- Not real people, but synthesized from info from real users
	- Should not be idealized
	- Brought to life with a name, characteristics, goals, and background
- Example of a Persona
	- ![[Persona example.png]]

### Methods for Data Gathering: Interviews, Focus Groups, Studying Documentation
- Five key issues for data gathering
	- Setting goals
		- decide how to analyze data once collected
	- Identifying participants
		- decide who to gather data from
	- Relationship with participants
		- clear and professional
		- Informed consent when appropriate
	- Triangulation
		- Look at data from more than one perspective
		- Collect different types of data
	- Pilot studies
		- small trial of main study (test procedure, equipment)
- Different structures/formats for interviews
	- **unstructured** - not scripted, rich but not replicable
	- **structured** - tightly scripted, like questionnaire - lack richness
	- **semi-structured** - guided by script, with flexibility
	- Question format can be closed (yes/no, 1-10, etc.) or open
- What to avoid in interviews
	- too long questions
	- compound questions
	- jargon
	- leading questions that make assumptions or indicate preferred answers (e.g., "so how much did you like that?")
- What's a way to ask questions that aren't biased for a certain answer?
	- What are your feelings while interacting with this?
	- What are your impressions about this?
- Procedure for interview
	- introduce yourself, explain goals, ask to record, informed consent...
	- start with easy warm-up questions
	- main body of questions in a logical order
	- cool off at the end with easy questions, let interviewee say whatever they want
	- closure and thank you
- Pro and con for interviews?
	- Pro: good for exploring issues, rich and data
	- Con: time consuming
- What is a focus group and what are pros and cons of it?
	- It's essentially a group interview about a product. It's good at gaining consensus views and highlighting conflict areas, but they can be dominated by individuals within the group
- What is researching similar products good for?
	- Prompting requirements to look at
	- What works well, what could be improved
- Why is it useful to study documentation?
	- Gives you a good understanding of legislation and getting background information about an activity or system
	- Takes no stakeholder time which can be a limiting factor on other techniques
	
	
### Methods for Data Gathering: Questionnaires + Indirect Observation
- What are the advantages of using questionnaires?
	- can be administered to large populations
	- can give both quantitative and qualitative responses (through open-ended questions)
	- good for getting specific responses form a large dispersed group of people, can be standardized and easy to answer
- What are disadvantages/issues with questionnaires?
	- needs very clear instructions on how to complete
	- need to balance detail and length
	- depends on the subjects' motivation, honesty, and ability to respond
	- maybe need to provide incentive
	- sampling, is it truly representative of the population of product's users or to everyone who saw the survey?
- What does it mean that something is validated?
	- It was experimentally verified that it measures what it is meant to measure - results from the questionnaire have been compared against results from other methods
- How can you design a questionnaire to filter out those who don't fill it out properly?
	- Ask the same question in different ways to see if there's consistency with the answers; if not, delete the incorrectly completed ones.
- Pros of online questionnaires
	- Responses are usually received quickly
	- no copying and postage costs
	- data can be collected in database for analysis
	- time required for data analysis is reduced
	- errors can be corrected easily
	- less perceived social pressure to be nice
- Cons of online questionnaires
	- Sampling is problematic if population size is unknown
	- Preventing individuals from responding more than once
	- Individuals have also been known to change questions in email questionnaires
	- self selection of respondents high
- What is indirect observation examples and how is it useful?
	- Automated tracking / using sensor data
	- It's useful when direct observation isn't possible, video observation is too intrusive, and provides long-term data collection and time stamping; usually combined with other forms of data collection
	- e.g., RFID tags & readers, activity sensors, location tracking, log files

### Methods: Observation, Video, Contextual Inquiry, Diaries
- Benefits of direct observation?
	- Gain insight into stakeholders' tasks
	- better understand nature and context of tasks
	- discovering unexpected things/anomalies
	- can provide a lot of data
- Cons of direct observation?
	- requires time and commitment
	- requires memory for data collection
	- different levels of intrusiveness varies the amount of detail
- How to structure observation?
	- Space: what is the physical space like and how is it laid out?
	- Actors: what are the names and relevant details of the people involved?
	- Activities: what are the actors doing and why?
	- Objects: what physical objects are present such as furniture
	- Acts: what are specific individual actions?
	- Events: is what you observe part of a special event?
	- Time: what is the sequence of events?
	- Goals: what are the actors trying to accomplish?
	- Feelings: what is the mood of the group and of individuals?
- Things to consider when conducting observation in the field
	- active observer or active participant? ethnographic (immersed into culture being studied)?
	- how to gain acceptance
	- how to handle sensitive topics
	- how will the data be collected (what data, what equipment, when to stop observing)
- What are downsides to video observation
	- some people may not want to be observed
	- may act different on camera
	- privacy issues (e.g., capturing face)
- Video observation is useful when you need to analyze
	- tasks that are done fast, and hard to observe in real time
	- when many people act simultaneously
	- when observer would be in the way or would distract/influence behavior
	- when personal observation would be dangerous
- What is a contextual inquiry?
	- a structured approach to ethnographic study where the user is the expert and the designer is the apprentice
	- it's a form of interview but at the users' workplace and is more unstructured
	- observe and ask: "why do you do it this way?", learn about shortcuts, fixes, what really happens in the environment
- Four main principles with contextual inquiries
	- context: see workplace and what happens
	- partnership: user and developer collaborate
	- interpretation: observations interpreted by user and developer
	- focus: project focus to understand  what to look for
- What's the outcome of a contextual inquiry?
	- a set of lists and models (main tasks & activities, flow model, sequence model, artifact model, physical model, cultural model)
- What's a diary study?
	- asks people to keep diary or journal of their interactions with a system, any significant events or problems during use of a system or other aspects of their working life
	- asks users to record date and time of events, location, information about event, log feelings, etc.

### Methods: closing remarks, mixing methods, considerations for data gathering, informed consent


- Considerations for data gathering
	- identify and involve stakeholders
	- how to involve stakeholders (workshops, interviews, workplace studies, include into development team)
	- political problems within organization
	- dominance of certain stakeholders
	- changing nature of economic and business environment
	- balancing functional and usability demands
	- requirements management (version control, ownership)
	- communication b/w parties (team, customer/user, other users who don't know the jargon)
	- availability of key people
- Why is informed consent important?
	- to protect privacy of participants and their anonymity
	- to protect vulnerable subjects (e.g., children, ill, elderly, etc.)
- Guidelines to gather data
	- focus on identifying **stakeholders' needs**
	- involve all stakeholder groups
	- involve more than one person from each stakeholder group
	- use combination of data gathering techniques
	- run a pilot
	- need to compromise on the data and analysis (feasibility, effort/outcome)
	- consider how to record the data

### Data Analysis
> Start analyzing data soon after gathering while it's still fresh in the mind. **Initial interpretations & Impressions** before deeper analysis, and different approaches emphasize different elements

- Ways to interpret and present findings
	- User profiles
	- describe scenarios and use cases
		- **scenarios:** informal narrative story, simple, natural, personal and not generalizable
		- **use cases:** assume interaction with a system and detailed understanding of the interaction
		- **essential use cases:** abstract away from details (e.g., UML diagram)
- Difference/relationship between persona, goal and scenario?
	- the persona describes **who** the story is about, the goal defines **what** the persona wants/needs to fulfill, and the scenario defines **when, where and how** the story of the persona takes place
- Different ways to illustrate use cases for a travel organizer
	- Sequence of interactions through text
		- The system displays options for investigating visa and vaccination requirements
		- The user chooses the option to find out about visa requirements
		- The system prompts the user for the name of the destination country
		- ...
	- Diagram
		- ![[Use Case Diagram Example.png]]