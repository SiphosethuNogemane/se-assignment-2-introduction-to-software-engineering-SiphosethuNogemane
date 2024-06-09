[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15221781&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:

*What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):*

Software engineering is a methodical, structured, and measurable approach used for creating, running, and managing software (Pressman, 2005, p20). It gives tools to address complications in a software system and allows for the creation of dependable software systems that optimize productivity (Khurana, n.d). The process of creating a program in traditional programming is manual, requiring the involvement of a programmer. However, in the absence of logic programming, rules must be manually formulated or coded (Insightsoftware, 2023). 

Studocu (n.d) list the following differences, Software engineering vs Traditional programming:

**Scope and Scale:** The field of software engineering involves creating intricate software systems that frequently comprise numerous modules, subsystem connections and components. Traditional programming, on the other hand, usually entails writing code for specific tasks or functionalities of a smaller-scale application.

**Methodology:** Throughout the software development lifecycle, including requirements analysis, design, implementation, testing, deployment, and maintenance, software engineering places a strong emphasis on the application of systematic techniques and best practices. Traditional programming may be primarily focused on coding duties, with no established procedure for managing the whole development lifecycle.

**Emphasis on Quality and Dependability:** Software engineering is heavily focused on making sure that software products adhere to strict requirements for maintainability, quality, and dependability. This entails thorough testing, documentation, code reviews, and conformity to established coding guidelines. Traditional programming may concentrate getting code to work above focusing on these quality criteria.

**Team Collaboration:** Software engineering frequently requires collaboration among diverse teams, which include software developers, testers, designers, project managers, and stakeholders. Completing sophisticated software projects successfully requires effective teamwork and communication. In traditional programming, people may work on coding projects alone and in a more lonely manner.

**Long-term Maintenance and Evolution:** Software engineering takes into account the long-term and evolution of software systems over an extended period of time, preparing for potential modifications and updates. This includes creating flexible and extensible software structures, as well as developing techniques for effectively managing software changes and upgrades. Traditional programming may prioritize instant solutions over long-term maintenance and scalability.



*Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.*

The Softare Development Life Cycle steps are described below (Free Learning Platform For Better Future, n.d) 

**Step 1: Planning**
In this stage, the project defines its scope and limitations, and conducts a feasibility study (including financial, operational, and technical evaluations) with input from business users. Example: A team decides to develop a web application for task management. They determine the project's scope, features, and timetable, and allocate a R100,000 budget over six months.
 
**Step 2: Design**
The product design process kicks off with a clear specification of requirements as defined in the Software Requirement Specification (SRS) document, which must be authorized by clients before design work can begin. Using the SRS, junior team members suggest and describe multiple product architectural designs in a Design describe Specification (DDS). Example:  Designers build logical mockups and wireframes for easy navigation and task visualization.

**Step 3: Develop**
Once the ideal design is chosen, execution starts immediately. Programmers create software in accordance with the DDS, following company standards for coding and utilizing company-provided resources. They document the given functions on a technical level in a Functional Specification (FS). Example:Developers utilize React and Node.js to build features such as user authentication and database models.

**Step 4: Test**
Software testing is essential at all phases, with two major rounds headed by programmers, end users, and quality assurance specialists. Programmers identify vulnerabilities, end users assure task alignment, and quality control professionals evaluate the product extensively, necessitating different test procedures for each group to achieve full testing. Example:Testers run unit, integration, and end-to-end tests and report defects for resolution.

**Step 5: Deploy**
The initial duty during the deployment stage is to validate all test cases to ensure that the software runs successfully. Management permission is required before deployment to the production environment, which necessitates a well-defined Deployment Plan (DP) and various guideline documents. Example: Then the stable application is delivered on cloud platforms with automated CI/CD pipelines to ensure user accessibility.



*Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Agile vsWaterfall:*

According to (Čarapić et al., 2023): 

**1. Strategy** - The approach of an organization that uses agile methodology depends on flexibility, responsiveness, and close connection with the client, whereas the strategy of an organization that uses Waterfall is based on efficiency, predictability, and ex-ante set estimates. 

**2. Structure** - When agile methodology is adopted, the organization's structure depends on small decentralized teams, which should not restrict self-organizing capacity with a size more than ten individuals. On the other side, the waterfall technique tends to result in a more centralized and formalized organization, with a greater power distance and a stricter hierarchy or chain of command. Teams are structured, and departmentalization is based on the criteria of the process stage (in terms of waterfall phases). 

**3. Processes** - In organizations that use agile methodologies, processes are less significant than other organizational factors.  The Waterfall method does not have a substantial impact based on its main process that determines the methodology, but the main process of software development has a strong impact on the other parts of the organization, which are mostly determined by the stage - e.g. requirements specification, design, coding, or testing.

**4. Reward system** - An organization's reward system becomes significantly more dynamic when agile methodology is used. As a result of the results being evident in increments that are several times smaller than those of the waterfall technique, there is less time spent waiting between performance and reward. 

**5. People** - When agile approaches are used in an organization, proactive, flexible employees are required. These employees are also far more likely to perform successfully, reach high performance standards, and advance in their careers. The competence triad shows that, in organizations using the Waterfall method, knowledge is largely consistent, knowledge of methodology primarily distinguishes skills, and attitudes show the greatest variation. The organization needs employees who follow their conscience rather than follow orders much more than it does. 

**Scenarios in which they are prefered** (Lockhart, 2023):

Waterfall project management is best effective for projects with clearly defined requirements, restricted complexity, and a definitive time frame. It works best in situations where client requests are specific and scope or technological changes are improbable. Waterfall projects have a straightforward scope and require minimal requirement gathering. They follow a linear and unambiguous work sequence with anticipated outputs depending on set deadlines. Its well-organized procedures guarantee the application of strict quality control standards, promoting confidence in project outputs. All parties involved must, however, maintain a sustained level of commitment for the Waterfall model to be applied successfully, ensuring that the set plan is followed for the duration of the project.

Agile project management is a powerful methodology that works well for projects with unclear end goals, complex systems that need constant feedback cycles, or limited budgets and schedules. Its adaptability is extremely useful, especially in software development, as it speeds up testing and modification throughout the entire process. Agile's effectiveness extends to circumstances that need strong collaboration across geographically distributed teams. It performs best in settings with complicated deliverables that call for regular revisions and improvements to satisfy changing needs. Agile creates collaborative environments that are suited to meeting the different interests of numerous stakeholders by facilitating rapid delivery and accommodating unanticipated needs.


*What is requirements engineering? Describe the process and its importance in the software development lifecycle.*

(Pressman, 2005, pp.256-261) states that:

Requirements Engineering provides the right framework to comprehend what the client wants, assess needs and feasibility, determine an appropriate solution by specifying the solution clearly, confirming the specification and managing the requirements as they are converted into a functional system.

**Process of Requirements Engineering**
1. **Elicitation Requirements:** Elicitation entails obtaining and comprehending information about both an existing system and the ideal system to be built. This information is gathered from a variety of sources, including historical documents, study findings, and human encounters (Burkin n.d)

2. **Analysis:** classifies and arranges requirements into related subgroups. examines each criteria in conjunction with others; examines the requirements for uniformity, omissions, and confusion. It classifies requirements according to the demands of customers/users.

3. **Specification:** The system and requirements engineer's ultimate output is the system specification. It is the foundation for software, database engineering, hardware, and human engineering. It outlines how a computer-based system works and performs, as well as the restrictions that will guide its development. The specification limits each assigned system element. 

4. **Validation:** Formal technical reviews are the main means of confirming requirements. The review team comprises users, system engineers, customers, and other relevant parties who scrutinize the system specification. They search for inconsistencies (a significant issue when creating large products or systems), contradictory requirements, and unreasonable (unattainable) requirements, as well as errors in content or analysis in areas that may require clarification, insufficient data, and inconsistent requirements.

5. **Management:** Requirements management is a collection of actions that assist the project team in identifying, controlling, and tracking requirements and changes to requirements at any time as the project advances. The first step in managing requirements is to identify them. Each requirement is allocated a unique identification that may take the form <requirement type><requirement #>, where requirement type takes on variables such as F (functional), D (data), B (behavioral), I (interface), and P (output).


**Importance Of Requirements Engineering In SDLC** (Burkin, n.d)

The development team uses the software requirements as a roadmap, which guarantees that all participants are pursuing the same objective. The significance of requirements engineering cannot be emphasized. It enables the development team to determine the scope of the project, define achievable targets, and prioritise features. 

Requirements engineering guarantees that the software product is of the highest quality, fulfills the needs of the client, and specified on time and within the allocated budget. A lack of adequate Requirements Engineering can cause substantial issues in the software development process. For example, insufficient or confusing specifications might cause miscommunication among the development team and the client, leading in a product that fails to satisfy the client's requirements.  

Requirements changes made during the development phase can result in delays and high project expenses. Requirements engineering best practices must be followed in order to reduce these risks. These procedures include determining the requirements and the needs of the stakeholders, formulating precise and succinct requirements, verifying the requirements, and maintaining the requirements current during the development process. 

Reducing the risks related to requirements engineering can also be accomplished by implementing an iterative methodology like Agile. Any software development project must have effective requirements engineering in order to guarantee that the final product will be of the highest quality, will satisfy the expectations of the client, and will be delivered on schedule and within budget.


**Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?*

**Modularity** - Is the process of disassembling a large, complex system into smaller, easier-to-manage parts or modules (GeeksforGeeks, 2024).

According to Free Learning Platform For Better Future (n.d) 

**Enhanced Maintainability:** One of the primary advantages of modularity is that it improves software maintenance. Separating distinct functions in a software system into different components - modules - allows you to update or correct a defect in one module without impacting the rest of the system. Working on one module without influencing the others makes debugging and maintenance easier. 

**Scalability:** Allows for rapid expansion or modification of a software system. To enable additional features or expand current features and functionalities, more modules can be introduced. Software systems need to be scalable in order to be able to change with the needs of the user. 

Modularity improves the maintainability and scalability of software systems through a variety of techniques. Modularity promotes worry isolation by compartmentalizing functionality into modular components, each accountable for specialized tasks, so simplifying comprehension, modification, and debugging. Furthermore, modular architecture encourages code reuse across multiple portions of the system, reducing redundancy and increasing consistency while speeding up development. Individual modules can be tested and debugged independently, making issue identification and resolution more rapid. Furthermore, modular systems are naturally scalable, allowing for the smooth integration of new capabilities through module addition or extension without disturbing the entire system. Modules improve productivity and accelerate time-to-market by removing dependencies and bottlenecks.

**Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?*

**Unit testing** - often known as program testing, is the process of testing each program individually in the system. It is often assumed that the goal of such testing is to ensure that programs are error-free, however this is realistically unattainable. Instead, testing should be considered as a method of locating flaws in programs, with the goal of identifying all of the ways in which a program might fail. Once identified, issues can be resolved.

**Integration testing** - is a methodical approach to building the program's structure while simultaneously testing to find interface-related mistakes. The goal is to take components that have been put through unit testing and use them to construct a program structure that is determined by design (Pressman, 2005). 

**System testing** - examines how well the entire software system operates. It seeks to ascertain whether there are differences between the system's intended functionality and its actual functioning, as well as whether separate parts will collaborate as intended. Performance time, recovery, file storage capacity, restart capabilities, manual procedures and peak load handling are among the areas covered.

**Acceptance testing** - certifies that the system is ready for use in an operational setting. Users do system testing, which are then assessed by management. After the new system satisfies everyone's requirements, it is officially approved for installation.

**Importance Of Software Testing**

Software testing is an essential step in the creation of high-quality software. Testing is vital since everyone makes mistakes. Some of these mistakes are minor, but others are costly and harmful. As a result, we must thoroughly inspect everything we create (Uddin & Anand, 2019).

Devi (2012) list the following importance of software testing:

1. **Identification of Bugs and Defects:** The rigorous testing procedure aids in finding and correcting any flaws that may affect the application, resulting in a more dependable and stable final output.

2. **Information to stakeholders and reputation of company:** A company's reputation can be improved by effectively testing and ensuring that stakeholders are aware of the company's dedication to high standards.

3. **Improvement in Product Quality:** This procedure aids in the identification and correction of faults, resulting in considerable product quality improvements.

4. **Technical Importance:** Testing is a critical step in the Software Development Life Cycle (SDLC) that ensures the application's technical integrity. It guarantees that the finished product satisfies all established technical standards and requirements and is technically solid and strong.

5. **To Get ahead of any Competitive Developers:** Thorough testing guarantees that the software is reliable, secure, and safe, giving it a competitive edge and encouraging development.

6. **Keep Away any Hazards:** Testing is an important element of software development since it helps to avoid potential risks for consumers. Untested software can carry considerable hazards. Thorough testing guarantees that the program is secure and trustworthy, thereby protecting users from potential danger.

7. **Improved Quality:** Continuous testing enhances software application quality, ensuring a secure and user-friendly experience.

8. **Verification and validation:** Testing is an important indicator in the V&V process since it allows for quality comparisons across different goods. It guarantees that the software meets the specifications and functions as intended.

9. **Reliability Estimation:** The application is tested thoroughly, from regression testing to unit testing, to guarantee its dependability. Testing produces a software product that is reliable by acting as an efficient statistical technique to determine operational performance.
    
10. **Prove Usability and Operability:** A critical goal of software testing is to verify that the software is useful and functioning. Usability testing is deploying the software to a small set of users and observing their interactions. 

11.  **Prevent Defect Migration:** Most problems occur during the software requirements gathering process. Early detection of faults helps prevent them from affecting future development phases.Early fault detection and debugging can significantly reduce software development costs.

12.  **Economic importance:** A well-tested software program will have a positive economic impact. People want trustworthy and reputable applications in the industry.


**What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.*

(Khleel et al., 2020) empahsizes on the following:

**Version control systems (VCS)** are a type of software project management tool that contains source code, configuration files, and documentation. 

**Importance Of The Version Control System**

The software development process can be sped up and made simpler with VCS. By facilitating cooperation and making it easier for individuals to exchange source code, Version Control Software (VCS) facilitates unrestricted teamwork. Individuals can work on any file at any time without accidentally writing over each other's work. When people commit changes, they produce a new version of the associated file. VCS professionally maintains the version. It is also possible to securely keep the previous version of the source code in the VCS repository thanks to VCS. A VCS is incredibly valuable since it allows individuals to recover from unintentional deletions or edits.

**Popular Version Control Systems And Their Feeatures**

1. Git, a distributed version control system, supports decentralized workflows by allowing developers to work separately and then merge changes. Its branching and merging capabilities enable concurrent development and experimentation. Git keeps a thorough history of modifications, which aids in problem identification and rollback. A staging area enables developers to examine and selectively commit changes. Git handles big repositories quickly and effectively. It uses cryptographic hashes to verify codebase integrity. Git is an open-source project with a large community that supports its development and provides new features (Ansari, 2023).
2. Helix Core - Software development teams can receive a powerful solution from Helix Core's artifact management and Perforce Streams' branching automation. In order to create a centralized repository for builds, Helix Core allows binary artifacts to be stored and versioned alongside code. Perforce Streams automates branching and merging, reducing expensive merge conflicts and improving development operations. Whether used on-premises or in the cloud, Helix Core's unbreakable security measures guarantee the protection of assets and intellectual property by limiting access and requiring identity verification. Helix Swarm also promotes international cooperation between development teams, which makes code reviews easier and code collaboration more effective. When combined, these solutions offer a complete platform for improved teamwork amongst geographically separated teams, safe code management, and expedited development processes (PERFORCE, n.d).
3. Team Foundation Server (TFS) is a robust version control system that allows for efficient administration of source files and artifacts in a centralized repository. TFS allows developers to store files centrally and manage multiple versions of source code, encouraging collaboration and assuring version control integrity. TFS makes work item management easier, allowing teams to keep track of task statuses as well as important details like assignments and progress. TFS makes it easy to automate build processes, allowing teams to create and manage product builds on a regular basis, hence increasing development efficiency. TFS provides project-specific portals that leverage Windows SharePoint capabilities, giving team members centralized access to documents, reports, and collaboration tools such as calendars and lists, resulting in improved communication and efficiency (Geeksforgeeks,2015).



**Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?*

The role of a project manager in software development encompasses several key responsibilities (Felici, n.d):

**Estimation:** Project managers are responsible for estimating the amount of effort, time, and money needed to complete a project. This entails examining project requirements, comprehending the scope of work, and effectively forecasting resource demands.

**Planning:** Using comprehensive plans, project managers specify the goals, deliverables, deadlines, and milestones of the work. They set review points to measure progress and assign people to different tasks based on their expertise and availability.

**Replanning:** As a project moves forward, conditions can change. For example, unanticipated hazards or problems with quality control could arise. To effectively adjust to changing circumstances, project managers must be capable of reestimating effort, time, and cost, as well as rescheduling work.

**Quality assurance:** It's critical to make sure the software product satisfies the necessary quality standards. Throughout the course of the project, project managers organize and carry out quality assurance procedures. This entails setting goals for quality, creating procedures for validation and testing, and quickly resolving any problems with quality that arise.

**Organization:** To guarantee that abilities are used efficiently and productivity is maximized, project managers create a division of labor within the project team. When allocating resources and promoting a productive and cooperative work environment, they take into account variables such as project complexity and risk.

**Challenges Faced In Managing Sotware Projects**

Navigating a number of obstacles is part of managing software projects, such as scope creep, resource management, risk reduction, failures in communication, quality assurance, change management, stakeholder involvement, complexity of technology, teamwork, and project governance. If these issues are not properly resolved, they may cause delays, overspending, and impaired project outcomes. Effective resource allocation, open communication, proactive risk management, and encouraging teamwork and stakeholder participation are all essential for project managers. Staying current with emerging technology and industry best practices is critical for successful project delivery. By tackling these issues with diligence and foresight, software project managers may improve project success and assure the timely delivery of high-quality software solutions (Kazmi, 2024).

**Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?*

According to the IEEE Standard for Software Maintenance, software maintenance is the act of altering a software product after it has been delivered in order to resolve bugs, enhance functionality or other aspects, or adjust it to a changed environment. The standard covers maintenance tasks before the software product is delivered as well, but only in an informational appendix. 

According to Pigoski (n.d)

**Maintenance Activities**
1. **Unique Activities:** Maintainers must have intimate knowledge of the code's structure and content. Maintainers utilize this knowledge to undertake impact analyses. Impact analysis analyzes all systems and products impacted by the modification request and estimates the resources required to implement the change.The risk of making the adjustment has been calculated. The change request, also known as a modification request or a problem report, must be reviewed and transformed into software terms. The maintainer then determines the impacted components. Several viable answers are presented, followed by a recommendation as to the best course of action. Maintenance requires strong problem-solving skills.Maintainers must additionally consider the "ripple effect" of any suggested changes. 

2. **Support Activities:** Supporting tasks including configuration management (CM), quality assurance, audits, reviews, and user training can also be completed by maintainers. Often, these supporting operations are handled by distinct businesses. According to the IEEE 1219 standard for software maintenance, continuous maintenance (CM) is a crucial part of the process. CM procedures should verify, validate, and certify each stage in identifying, authorizing, implementing, and releasing software products. Maintainer training is an important supporting activity.
   
-**Configuration Management:** It is insufficient to just log change requests or problem reports. Control is required over the software product and any modifications made to it. An authorized software configuration management (SCM) procedure must be put into place and enforced in order to create this control. SCM supports and simplifies the job of the maintenance. In contrast to development, SCM for maintenance begins with a change request. Creating and adhering to a CM Plan and operational procedures is how the SCM process is put into practice. In order to decide when improvements should end and whether a migration is required, maintainers take part in Configuration Control Boards. The severity of a problem frequently determines how and when it will be addressed.

**Quality:** Maintaining software does not automatically lead to improved quality. Effective maintenance requires planning and implementation of processes. To reach desired quality levels, Software Quality Assurance (SQA) and Verification and Validation (V&V) activities and methodologies should be chosen in conjunction with other processes. This involves creating and following SQA and V&V strategies and processes.

3. **Maintenance Planning Activity:** Planning is a key step in software maintenance.The operation and maintenance phase usually lasts for several years, while developments usually last for one to two years. One of the most important aspects of maintenance planning is creating precise resource estimates. Project planning budgets should account for resources, including expenses. Quality objectives should be taken into consideration when starting the maintenance planning process, starting with the choice to build a new system. Develop a concept, followed by a maintenance strategy. (Pigoski,n.d)


**Importances Of Maintenance**

Maintenance is an important aspect of the software lifecycle for a variety of reasons. First, software systems grow over time to meet evolving user wants, technology advancements, and corporate objectives. Maintenance enables continuous modification and enhancement of software to guarantee that it stays relevant and effective in fulfilling these changing needs. Second, software maintenance is critical for dealing with faults, bugs, and performance issues that emerge beyond the initial development period. Regular maintenance tasks, such as debugging, troubleshooting, and performance optimization, help to guarantee that software runs smoothly and efficiently. Maintenance is required to ensure the security of software systems by resolving vulnerabilities and applying patches that guard against cyber threats. A software product's lifespan can be increased with maintenance, increasing its return on investment and lowering the need for pricey replacements or redevelopments. Overall, maintenance is critical to the long-term performance, usefulness, and sustainability of software systems.
 

**What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?*

Accroding to (Gomes et al., 2023) the following are the ethical issues and the ways to adhere to ethical standards:

Security refers to the system's capacity to store data while also protecting it in such a way that hostile actors cannot gain access. This is of particular importance given the amount of data that each individual user generates. It is critical that this data, as well as internal organizational data, remain safe. 

Privacy is concerned with identity, as well as the collection, storage, and identification of individuals based on data. The issue of security is similarly essential due to the volume of data created, but it focuses on the importance of maintaining users' anonymity as well as challenging the purpose of collecting this data. 
Transparency is currently being challenged, primarily in the field of AI. AI algorithms are typically opaque, making decision-making difficult to understand. 

The urgency of the situation prompted a discussion on how to improve system usability. This problem is strongly linked to the explainability and explicability problems, which are concerned with comprehending and elucidating artificial intelligence systems. 

Fairness tackles the issue of partiality. This component, which is described as "fair or impartial treatment" by the Merriam-Webster dictionary, tries to get people to critically consider how to create systems that don't discriminate against someone because of their skin color, age, gender, or any of the many unique qualities that make one human. 

**Adherence To Ethical Standards**

Software engineers uphold ethical standards in the workplace by studying and following established norms and codes of behavior. They put user privacy and security first, putting in place strong safeguards to protect personal data and guaranteeing transparency in data handling methods. Engineers are actively working to reduce bias and discrimination in software systems, aiming for fair and equal outcomes. They implement ethical decision-making processes throughout the development lifecycle, conducting impact assessments, involving stakeholders, and obtaining expert advice when confronted with complicated challenges. Continuous learning and improvement are essential, as engineers stay current on developing ethical challenges and best practices, so contributing to the development of technology that helps society ethically.

**REFERENCES**

1. Ansari, F. (2023) What is a git: Know features, commands, and workflow, Hatica. Available at: https://www.hatica.io/blog/git-features-command-workflow/ (Accessed: 09 June 2024). 
2. Burkin, V. (no date) Mitigating Risks in Software Development through Effective Requirements Engineering, ResearchGate. Available at: https://www.researchgate.net/publication/370656291_Mitigating_Risks_in_Software_Development_through_Effective_Requirements_Engineering (Accessed: 09 June 2024). 
3. Devi, T.R. (2012) Importance of Testing in Software Development Life Cycle, 3(5). doi:ISSN 2229-5518. 
4. Felici, M. (no date) ‘Project Management’, The University of Edinburgh. Available at: https://www.inf.ed.ac.uk/teaching/courses/seoc/2006_2007/notes/LectureNote07_ProjectManagement.pdf (Accessed: 09 June 2024)
5. Free Learning Platform For Better Future (no date) Modularity in software engineering - javatpoint, Free Learning Platform For Better Future. Available at: https://www.javatpoint.com/modularity-in-software-engineering (Accessed: 09 June 2024)
6. Geeksforgeeks (2015). “What Is Team Foundation Server?” GeeksforGeeks, www.geeksforgeeks.org/what-is-team-foundation-server/. Accessed 9 June 2024. 
7. GeeksforGeeks (2024) Introduction to modularity and interfaces in system design, GeeksforGeeks. Available at: https://www.geeksforgeeks.org/inroduction-to-modularity-and-interfaces-in-system-design/ (Accessed: 09 June 2024). 
8. Gomes, O.S., Braga e Silva, G. and de Souza, É.F. (2023) ‘Ethics in the Software Development Process: A Tertiary Literature Review’, Ethics in the Software Development Process: a Tertiary Literature Review, pp. 2–3. doi:10.5753/washes.2023.229923. 
9. [IEEE1219] IEEE STD 1219: Standard for Software Maintenance, 1998. 
10. Insightsoftware (2023) Traditional programming vs machine learning, insightsoftware. Available at: https://insightsoftware.com/blog/machine-learning-vs-traditional-programming/
11. Kazmi, R (2024). “Common Project Manager Challenges in Software Development.” Koombea, www.koombea.com/blog/project-manager-challenges/.
12. Khleel, N.A.A. and Nehéz, K. (2020) ‘Comparison of version Control System Tools’, Multidiszciplináris Tudományok, 10(3), p. 69. doi:10.35925/j.multi.2020.3.7. 
13. Khurana, R. (no date) ‘Software Engineering’, in Vikas Publishing . New Delhi, India: Vikas Publishing House. Available at: www.vikaspublishing.com. 
14. Lockhart, L. (2023) Agile vs. waterfall: 10 key differences between the two methods, Float. Available at: https://www.float.com/resources/agile-vs-waterfall (Accessed: 09 June 2024). 
15. PERFORCE (n.d). “Top Version Control System — Perforce Helix Core | Perforce.” Www.perforce.com, www.perforce.com/solutions/version-control. Accessed 9 June 2024. 
16. Pigoski, Thomas M. “SOFTWARE MAINTENANCE.” Technical Software Services (TECHSOFT), Inc. , pp. 6–9. https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=cce379aafc9a48df5700ca1c649482893bd5be06.
17. Pressman, R.S. (2005) . ‘Software Engineering A practitioner’s Approach’, in Google books, p. 21. Available at: https://books.google.co.za/books?id=bL7QZHtWvaUC&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=true. 
18. Studocu (n.d) “[Solved] What Is Software Engineering and How Does It Differ - Computer Literacy Advanced (HCLT108-1) - Studocu.” Www.studocu.com, www.studocu.com/en-za/messages/question/7612125/what-is-software-engineering-and-how-does-it-differ-from-traditional-programming. Accessed 9 June 2024. 
19. T h e H o n g K o n g U n i v e r s i t y o f S c i e n c e a n d T e c h n o l o g y (no date) Software development life cycle. Available at: http://home.cse.ust.hk/~rossiter/independent_studies_projects/software_development/software_development_report.pdf (Accessed: 09 June 2024). 
20. Uddin, A. and Anand, A. (2019) Importance of Software Testing in the Process of Software Development , 6(12). doi:ISSN (online): 2321-0613 . 
21. Čarapić, A., Čudanov, M. and Jaško, O. (2023) ‘Comparative analysis of waterfall and agile approach to organisation in the star model context’, COMPARATIVE ANALYSIS OF WATERFALL AND AGILE APPROACH TO ORGANISATION IN THE STAR MODEL CONTEXT, pp. 516–516. doi:10.46541/978-86-7233-406-7_260. 