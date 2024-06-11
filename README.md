[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15242440&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
1Define Software Engineering:
Software engineering is the full development life cycle of computer systems that run on a computer . It involves the design, development, testing, deployment, and maintenance of software products.

2What is software engineering, and how does it differ from traditional programming?
Software engineering is broader and focuses on the development from beginning to end. It involves the design, development, testing, deployment, and maintenance of software products.
Traditional programming is more narrow and just focuses on the coding part of development

3Software Development Life Cycle (SDLC):
4Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Requirements: Collecting and recording user needs and system specifications.
Design: Developing both high-level and detailed plans for the software architecture and user interface.
Implementation: Coding and constructing the software based on the design plans.
Testing: Performing various tests to verify the software's quality and functionality.
Deployment: Distributing the software to users or customers.
Maintenance: Offering continuous support, updates, and improvements to the software post-release.

5Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Aglie is an adaptive software development methodolgy and it is used when requirements are not well understood and theres a high techincal risk ,it focuses on iterative and an incremental approach to software development.

Waterfall is a predictive approach which assumes projects can be planned out in advance ,requirements are well understood and when we have low risk.It follows a sequential ,waterfall development process and you cant go back to the previous step.It goes from planning,analysis,design and then implementation 

6Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements engineering is the process of gathering stakeholder input,requirements for the software we are trying to build and and we can use things like questionnaries ,surveys,researching vendor soultions,set interviews etc to get to know what the stakeholder need from the software.This ensures that user needs are met and there arent any mismatches between what is required and what is developed.That is analysis of requirements and we can also group them into non-functional and functional requirements and get to see whats importanst and whats nice to have for the software .From there we move on to requiremenst specifications here we draft a document detailing use cases,which includes use case diagrams and descriptions we can include activity diagrams ,functional and non functional requirements,state machine diagrams etc.From there we move onto requirments validation this ensures the documentated requirments accurately reflect stakeholder requirements.Its important to do this because we need to ensure that stakeholder needs are met when the software is developed.This can also reduce scope creep ,it can set a foundation for development and most importantly it ensures users are involved in everything.

Software Design Principles:
7Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Dividing a software system into separate, self-contained pieces (modules) that communicate with one another via well defined interfaces is known as modularity.The code is essesstially broken down into pieces called modules ,functions and each pieces contributes a single task to the entire program,the modules can be called and we make use of parameters.

Advantages of Maintaining Modularity:

Modification Isolation: Modifications made to one module hardly affect other modules.
Simplified Debugging: Problems with isolated modules are easier to find and address.
Reusability: Modules can be utilised again in other projects or in other sections of the application.
Simpleness of Understanding: It is simpler to understand and handle smaller parts.

Scalability
Independent Development: Various teams are able to work on various modules at the same time.
Module distribution can enhance load handling by distributing them among multiple servers.
Incremental Upgrades: Individual modules can be changed or upgraded.
Resource Allocation: Performance can be improved by optimising critical components.

Testing in Software Engineering:
8Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Software Testing Levels: 
Unit Testing
Emphasis: Individual parts.
Goal: Confirm that every module operates as intended.
Significance: Prevents errors in programming and guarantees its accuracy.

Integration Testing :
Emphasis: Interactions among the modules.
Goal: Guarantee that modules are interoperable.
Significance: detects flaws in the interface and guarantees integrated functionality.

System Testing
Highlight: A comprehensive, cohesive system.
Verify that the system satisfies requirements is the goal.
Makes sure the system performs as planned in a setting similar to production.

Acceptance Testing :
Final user system is the main focus.
Goal: Ascertain that the system satisfies user needs.
Importance: Verifies that software meets business requirements and is prepared for deployment.

 Importance:
High standards are ensured and flaws are avoided via quality assurance.
Reliability: Boosts robustness by locating and fixing flaws.
User satisfaction: Enhances user experience and satisfies user requirements.
Cost Efficiency: Lowers expenses and labour by finding flaws early on.
Risk management provides stability and security by identifying problems prior to deployment.

Version Control Systems:
9What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software tools for tracking changes to source code and coordinating work among team members (e.g., Git, Subversion).
6
Git Distributed Version Control features include flexible collaboration and offline work.
Branching and Merging: strong merging capabilities combined with a light branching structure.
Performance & Speed: Most processes are carried out locally, and the system is designed for speed.
Data Integrity: Makes use of cryptographic hashing to guarantee the accuracy of repository data.
Before committing, the staging area (index) allows for the selective staging of modifications.
Rich Toolkit: Numerous utilities and version control tools.
Huge Community: A vibrant community with a wealth of assistance and documentation.
Citations:

Visit https://git-scm.com/doc for the Git documentation.
Git-Scm.com/book/en/v2 Pro Git Book


Software Project Management:
10Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Software project management involves guiding a team's efforts to accomplish project objectives within specified limitations, such as scope, schedule, and budget. It plays a crucial role in ensuring:

- Punctual Completion: Maintaining project timelines.
- Financial Oversight: Supervising expenses to avoid exceeding budgets.
- Quality Assurance: Guaranteeing the end product meets prescribed criteria.
- Resource Optimization: Efficiently utilizing available resources.
- Risk Mitigation: Identifying and addressing potential risks.

Challenges in Software Project Management

Scope Expansion: The inclination for project scope to grow beyond initial specifications, resulting in elevated expenses and timeframes.
Resource Limitations: Constrained access to proficient personnel, financial restrictions, and time constraints can present obstacles in project implementation.

Software Maintenance:
11Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Maintenance of Software
Updating and changing software to fix bugs, enhance functionality, adapt to new settings, and guarantee continued usability is known as software maintenance.

Categories of Maintenance Tasks
Corrective maintenance involves fixing flaws and faults that were found in the programme while it was still in use.
Adaptive maintenance is the process of changing software to take into account modifications to its external environment, like new operating systems or hardware.
Perfective maintenance is the process of improving a piece of software's functionality or performance in response to user input or changing needs.
Preventive maintenance involves proactively detecting and fixing possible problems to stop them before they become bigger ones.
Maintenance's Significance Throughout the Software Lifecycle

Maintenance is essential for:

ensuring the operation and dependability of software throughout time.
software adaptation to changing user requirements and technology environments.
maximising return on investment through increasing software systems' longevity and worth.
Citations:

In 2016, Sommerville, I. Software Development. Wesley-Adobe.
Atlee, J. M., and S. L. Pfleeger (2015). Engineering Software: Concepts and Applications. Pearson.


Ethical Considerations in Software Engineering:
12What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Privacy Concerns and Ethical Issues in Software Engineering managing and making sure that private user information is protected.
Discrimination & Bias: Creating algorithms and systems that don't support or reinforce prejudices or discriminate against particular populations.
Developing secure software to stop breaches and safeguard user data is one way to address security vulnerabilities.

Respecting Ethical Guidelines
Ongoing Education: Through professional development and training, stay current on ethical standards and best practices.
Ethics Review: To find and fix such problems, conduct routine ethical evaluations of projects and code.
Openness and Responsibility: Be transparent in your communication with stakeholders regarding ethical issues and assume accountability for making moral decisions.

Johnson, D. G. (2016). Computer Ethics. Prentice Hall.
Gotterbarn, D. (1991). Software Engineering Code of Ethics. Link

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].

Name:Alimerinda Mlambo 
## I made use of AI and my notes from school and google..
