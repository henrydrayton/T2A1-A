# T2A1_A Henry Drayton

## Describe the architecture of a typical Rails application

Ruby on Rails is an additional open-source framework for the Ruby language that supports back-end application development. The Rails framework follows the Model, View and Controller (MVC) architectural structure, allowing for greater agility and maintainability within applications. 

### Controller
The controller handles all client requests from the browser and interacts with the server telling it what to do with these requests. The controller acts as the middleman for the model and the view elements and should not contain a lot of code. After receiving a client request, the controller then communicates with the model asking it to perform a certain function within the database. Rails applications utilise databases to store large amounts of backend information relevant to the product. 

###Model
The model is responsible for all interactions with the database, such as validation, saving, deleting and updating. After receiving a request from the controller, the model will perform one of these functions on the database and return the information to the controller. An example of this would be to retrieve all usernames starting with the letter “J”. The controller, in this case, would then pass all of the relevant usernames to the view module for conversion into graphical code.

###View
As mentioned above, the view module handles all information drawn from the database after being passed on from the controller. The view element can convert data to several formats other than HTML, such as PDF, XML and RSS. Once converted, the data is then sent back to the controller and presented to the client completing the request-response model.

##Identify a database management system (DBMS) commonly used in web applications (including Rails) and discuss the pros and cons of this database

PostgreSQL is an advanced open-source database management system that is the first choice for many developers and successful companies. Like any system, the database comes with its advantages and disadvantages. 

###Pros

- One of the most attractive features of this database management system, especially to startups, is the fact it’s open-source. The system is managed and maintained by a highly skilled community of developers and has an extensive library of additional plug-ins for more significant optimisation. 
<br>  
- The database supports Linux, Mac and Windows and caters for advanced data types, including JSON and geographic objects.
<br>  
- The database has built-in security features and also has the ability for additional restrictions to be applied.
<br>   
- PostgreSQL has advanced scalability features that allow startups to grow without worrying about switching over to a privatised database system.

###Cons
- The fact that PostgreSQL is open-source also comes with its downfalls. Database systems such as Oracle, MongoDB and Microsoft SQL are managed by massive companies meaning they come with warranty, liability and indemnity protection features PostgreSQL does not. 
<br>
- The performance of PostgreSQL can also be considered a downfall. The system reads the data in the table from top to bottom, meaning data structures with many rows and columns may reduce performance speeds. 

##Discuss the implementation of Agile project management methodology

The Agile methodology is highly beneficial to software developers and their companies alike. The standard development framework of plan, design, build, test, deliver is more suited towards physical manufacturing and does not consider the rapid growth of the software industry.  Tech companies are often bombarded by new hardware, software, demand and competition and need to stay relevant to establish their credibility. Companies using the Agile methodology aim to have a saleable product up and running within 2-4 weeks, with further development occurring after this. 

The Agile methodology often favours the SCRUM framework as it is centred around the concept of sprints. The SCRUM framework requires all developers to work collaboratively on one product for a short time, producing beneficial feedback from consumers.

Companies such as ACME Corporation looking to implement Agile project management must first undertake several considerations and steps.

###Vision and Goals
The Agile framework is excellent when it matches the company’s goals and culture; however, it is not suited for every business. Before implementing the Agile methodology, the company should arrange several meetings to establish who the target user will be, what product will produce the most valuable results and how the new methodology will impact their staff’s performance. 

###Strategic Planning and Roadmaps
Before completely switching over to this new framework, it is good to start small and build up accordingly. This means choosing one product to develop, define priorities, outline time periods, specific roles, and talk to relevant stakeholders. 

###Sprints
Sprints are fundamental to the Agile methodology’s success and require adequate planning. The framework cannot occur without every team member working collaboratively and empowering to achieve the same goal. An initial sprint meeting should be held before commencing any project, followed up by daily fifteen-minute stand-ups to communicate progress and concerns. Finally, a review sprint meeting should be held after a project discussing how the process can be improved in the future. 

##Provide an overview and description of a standard source control workflow

Source control is a way of managing code files often in a collaborative manner, ensuring all changes are incrementally documented and restricting others from overwriting code. Git and GitHub are the most popular source control tools for developer teams. 

The Git flow is categorised by several features:

###Repository
The repository is the term used to describe the container holding all files relevant to the project. Like the rest of Git, the repository has version control, a timeline of code files that updated versions won’t override. 

###Branch
Branches are subsidiary to the repository and allow developers to create and test new code in an isolated environment without affecting the working versions. 

###Commit 
After a repository and at least one branch is created, the developers can now commit their source code to GitHub. Committing is the term used for adding, editing or deleting code and should be done often. When committing files to GitHub, present tense descriptions must be added to each commit to communicate with other developers about what change was made in the file. 

###Merge
When all code has been reviewed and tested, it should be merged into a separate branch, often called a ‘parent branch’. This branch should hold all working code ready for production. If the code has errors upon merging for some reason, the code can still be rolled back and edited in the previous ‘child branch.’

##Provide an overview and description of a standard software testing process (e.g. manual testing)

Before software is deployed to the customer, it must first undergo rigorous testing to ensure no bugs are present. There are several testing methods, both automated and manual, each having its own individual value. When used in conjunction with one another, user experience and program workflow can be optimised. 

The standard manual software testing procedure is as follows:

1. Identify what elements of the software need to be tested. These elements should be divided into separate procedures being, unit testing (individual components), integration testing (several units in order), system testing (the entire software) and acceptance testing (feedback from developers and expected users). 
<br>
2. All tests should be planned clearly and logically to ensure they target specific outcomes and software requirements. 
<br>
3. Before testing commences, all tests should first be reviewed by a senior staff member.
<br>
4. Carry out all tests in an orderly manner and record any bugs that have occurred. 
<br>
5. Review all bugs, implement changes in the code to fix them and then carry out testing again, adjusting the tests if need be. 

##Discuss and analyse requirements related to information system security and how they relate to the project

As technology advances at such a rapid pace, companies such as ACME Corporation need to take adequate measures to plan, prevent and combat cyber attacks. Some general security requirements include:

###Integrity
Data retained by ACME Corporation must first be categorised depending on its level of classification. For example, data relating to what a user has purchased will require fewer security implementations than their credit card details. All data needs to be secure from cybersecurity attacks, and by choosing what is of most importance, developers can implement changes to specific areas of the software to combat this.  

###Authentication and Authorisation
Authentication methods are essential for securing sensitive data and should be implemented wherever necessary. Authentication verifies the user’s identity and provides them with specific access depending on their status. For example, an intern will have limited access to data than that of a senior software developer. 

###Cross-Platform Data Protection
To prevent the subversion of ACME from cyber-attacks it is a good idea to have mirroring databases. This not only prevents hackers from corrupting the whole business but also from their staff accidentally altering data. 

##Discuss common methods of protecting information and data and how you would apply them to the project

To prevent cybersecurity attacks, ACME Corporation should use a multi-layered approach to their protection model. In short, this means having several security methods working harmoniously, leaving little room for weak points. Standard procedures that have been tried and tested are: 

###Security Gateways 
Security gateways trace traffic and restrict foreign parties from accessing sensitive networks. Security gateways can be implemented in several ways, such as preventing breaches in company policies by limiting access to user data for only essential staff. They can also prevent and detect malicious software and bugs from entering a network, potentially corrupting and leaking classified data. Security gateway software is often purchased from an external third party company. 

###Authentication
Authentication refers to how a user or staff’s credentials are validated upon entering a program and is often seen in the form of passwords, pin codes, facial recognition and fingerprints. The sole purpose of authentication methods is to prevent malicious intruders from accessing personal information or data. In the case of a digital marketplace, facial recognition and fingerprints may be too excessive for the type of data being stored. They could also lead to a loss of business performance. ACME should, however, implement specific password requirements such as ten characters containing both digits and symbols or even expiring passwords depending on the class of data. 

Security gateways and authentication are only two of many ways to mitigate cybersecurity breaches. Both requirements should be implemented and validated before the marketplace is deployed to the public. 

##Research what your legal obligations are in relation to handling user data and how they can be met for the project

Consumer data is becoming ever more fundamental to a businesses success; however, if leaked into the wrong hands, this sensitive information could have severe physical and mental implications. There are several legal obligations regarding how user data is handled, and it is up to the developers to satisfy these requirements. 

Users need to be informed about what data is being collected, how it is being used and potentially transferred to third parties. This information cannot in any way be misleading to the user and should be made readily accessible. As a developer, it is good to express critical points upon initial signups and include complete documentation elsewhere on the application. As well as this, users must be able to view, edit and destroy all personal data. 

It is up to the company to invest in adequate security measures and developers to identify and report potential flaws in the model. In the event of a data breach, by law, the company needs to inform those affected. This law falls under the 1998 Australian Privacy Act. 

##Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

Relational databases are a powerful way of storing logical data points using a collection of tables. The table structure consists of columns and rows. Columns hold groups of categorical information, and rows, otherwise known as tuples, hold corresponding data relevant to a specific element. 

All tables relate via primary and foreign keys, used to navigate and perform functions on specific data. The primary keys are dominant categories used to link related tables. Foreign keys are primary keys listed in a corresponding table. 

The system works in a logical structure and is best represented in a visual format. 

![Foreign/Primary Keys](T2A1-A/foreignkey.jpeg)

Depending on the attributes in the tables, the tables can have one to one, one to many or many to many relationships. 

###One to One

![One to One](T2A1-A/OneToOne.png)

###Many to One

![Foreign/Primary Keys](T2A1-A/ManyToOne.png)


###Many to Many
![Foreign/Primary Keys](T2A1-A/ManyToMany.png)