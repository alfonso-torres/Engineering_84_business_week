# Interview preparation notes including questions and answers

## Questions

- Question 1: Tell me about yourself?
- Question 2: What is Agile and benefit of implementing it?
- Question 3: Why Sparta Global?
- Question 4: What is Scrum and benefit of implementing it?
- Question 5: Where do you see yourself in 2-5 years time?
- Question 6: What is DevOps and the benefit of using it?

### Answers

- Answer 1: My name is Jose Alfonso. I am a graduate in computer Science. During my university stage I developed different projects but I would like to highlight the creation of an application in the platform Android studio developed in Java, as well as its repectic connection to the databasein MySQL. Other project that has helped to learn a lot of, it was the creation of a cluster and its respective configuration. For this project, I have managed the use of virtual machines with linux operatyng system, as well as shell and command language of bash script. I started of my career as a membur of DevOps Department in Spain. It was a internship during 6 months. I was envolved in projects related to the deployment of infrasctrucure and process of automation. To be able to do my tasks I have learnt skills related to the concepts of Red Hat Linux and Ansible tool.

- Answer 2: Agile describes a set of guiding principles that use an iterative approach to project or software development. Agile methodologies are those that allow adapting the way of working to the conditions of the project at all times. For Agile to be implemented, it takes into account processes and technologies. In the case of processes, these must seek customer satisfaction, while adapting to the culture of the company. They are beneficial for the reason that it is easy to accommodate changes at any time and phase of the project, it generates a lower cost and a shoerter work time and because changes can be adopted during the course of the project.

- Answer 3: As soon as I see that you provide the role of DevOps I applied directly. You help people providing a specifc training to speciliaze in the role that they would like to be. This is the best way because you make people to be ready to start a career on the labor market. When I finished my degree I felt that I need to be more professional and with your program I will achieve my goals.

- Answer 4: Scrum is a specific set of rules that must be followed while practicing software development. It is a process in thw way that a set of good practices is applied on a regular basis to work collaboratively, as a tema, and obtain the best possible result from a project. They are beneficial for the reason that make an alignment between the client and the development team, the team can work with flexibility and adaptation.

- Answer 5: During my professional career I hope to learn enough knowledge and the necessary experiences to become an example as a DevOps Engineer. I want to be a consultant capable of solving any problem. I would like my role to develop through the path of DevOps Architect, to be abelt to carry out the design and implementation of business apliccations. I hope to achieve my goal by participating in great projects with good teams that help me improve.

- Answer 6: DevOps is an acronym for development and operations, which refers to a software development methodology that focuses on communication, collaboration, and integration between software developers and IT professionals. The benefits of using it is that it involves multidisciplinary teams, continuos improvement is the core of this methodology and it is based on collaboration to get good results.

### SQL

***Q&A***

- Question 1: What is a JOIN function?<br/>
A JOIN clause is used to combine rows from two or more tables, based on a related column between them. SQL JOIN two tables related by a single column primary key or foreign key. The different types of JOINs in SQL are:
1. INNER JOIN: returns records that have matching values in both tables.
2. LEFT JOIN: returns all records from the left table, and the matched records from the right table.
3. RIGHT JOIN: returns all records from the right table, and the matched records from the left table.
4. FULL JOIN: returns all records when there is a match in either left or right table.

- Question 2: What is a primary key and foreign key? What are their functions?<br/>
The primary key is a specific choice of a minimal set of attributes (columns) or only one attribute that uniquely specify a tuple (row) in a relation (table). A primary key must be unique. The value must never change. Each table may have a maxium of one primary key. Must walways have an entry, can not be NULL. It can be simple or compound. Simple corresponds only one field.Or composite, that combines more than one field (column). 
The foreign key is a field (or collection of fields) in one table, that refers to the primary key in another table. It is a referential limitation between tables. So they are used to create solid relationships. There is not uniqueness constraint for foreign keys. A table is allowed to contain more than one foreign key. Also, it is OK from them to contain NULL values.

- Question 3: What is DML and DDL?<br/>
They are structured query language. Is a domain-specific language used in programming and designed for managing data held in a relational database management system.
1. Data Manipulation Language (DML): used for adding, deleting and modifying data in database. -> SELECT, INSERT UPDATE and DELETE.
2. Data Definition Language (DDL): used for creating and modifying database objects suchs as tables, indices and users. -> CREATE, ALTER, DROP and TRUNCATE.

- Question 4: What is Normalisation?<br/>
Normalisation is the process of structuring a database, usually a relational database, in accordance with a series of so-called normal forms in order to reduce data redundancy and improve data integrity. Types of normalization:
1. First Normal Form (1NF): make everything atomic. There should be not repeating groups.
2. Second Normal Form (2NF): Be in 1NF. All non-key attributes are fully functional dependent on the primary key. There should be no partial dependency.
3. Third Normal Form (3NF): Be in 2NF. It does not have transitive dependency.

- Question 5: What is Entity relationship diagram and benefit of using it?<br/>
An entity relationship diagram (ERD) shows the relationship of entity sets stored in a database. Is a type of structural diagram for use in database design. It contains different symbols and connectors: the entities and the inter-relationships among these entities. To fully utilize ER Diagram in database engineering guarantees you to produce high-quality database design to use in database creation, management, and maintenance. An ER model also provides a means for communication.

### What is Git and Git-hub and benefit of using it?

- Git is a version control software, thinking about the efficiency, reliability and compatibility of the maintenance of versions of applications. The purpose is to keepp the track of changes in computer files including coordinating the work that various people do.
- Git-hub is a online repository. It lets you and others work together on projects from anywhere. All is saved on a cloud. <br/><br/>
Regarding the benefits, it makes it easy to contribute to your open source projects, it makes it easier to get excellent documentation, it is a repository that allows your work go get out there in front of the public and it can track changes in your code across versions.
