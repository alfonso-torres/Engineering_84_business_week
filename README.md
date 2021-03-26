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

## SQL

***Q&A***

- __Question 1: What is a JOIN function?__<br/>
A JOIN clause is used to combine rows from two or more tables, based on a related column between them. SQL JOIN two tables related by a single column primary key or foreign key. The different types of JOINs in SQL are:
1. INNER JOIN: returns records that have matching values in both tables.
2. LEFT JOIN: returns all records from the left table, and the matched records from the right table.
3. RIGHT JOIN: returns all records from the right table, and the matched records from the left table.
4. FULL JOIN: returns all records when there is a match in either left or right table.

- __Question 2: What is a primary key and foreign key? What are their functions?__<br/>
The primary key is a specific choice of a minimal set of attributes (columns) or only one attribute that uniquely specify a tuple (row) in a relation (table). A primary key must be unique. The value must never change. Each table may have a maxium of one primary key. Must walways have an entry, can not be NULL. It can be simple or compound. Simple corresponds only one field.Or composite, that combines more than one field (column). 
The foreign key is a field (or collection of fields) in one table, that refers to the primary key in another table. It is a referential limitation between tables. So they are used to create solid relationships. There is not uniqueness constraint for foreign keys. A table is allowed to contain more than one foreign key. Also, it is OK from them to contain NULL values.

- __Question 3: What is DML and DDL?__<br/>
They are structured query language. Is a domain-specific language used in programming and designed for managing data held in a relational database management system.
1. Data Manipulation Language (DML): used for adding, deleting and modifying data in database. -> SELECT, INSERT UPDATE and DELETE.
2. Data Definition Language (DDL): used for creating and modifying database objects suchs as tables, indices and users. -> CREATE, ALTER, DROP and TRUNCATE.

- __Question 4: What is Normalisation?__<br/>
Normalisation is the process of structuring a database, usually a relational database, in accordance with a series of so-called normal forms in order to reduce data redundancy and improve data integrity. Types of normalization:
1. First Normal Form (1NF): make everything atomic. There should be not repeating groups.
2. Second Normal Form (2NF): Be in 1NF. All non-key attributes are fully functional dependent on the primary key. There should be no partial dependency.
3. Third Normal Form (3NF): Be in 2NF. It does not have transitive dependency.

- __Question 5: What is Entity relationship diagram and benefit of using it?__<br/>
An entity relationship diagram (ERD) shows the relationship of entity sets stored in a database. Is a type of structural diagram for use in database design. It contains different symbols and connectors: the entities and the inter-relationships among these entities. To fully utilize ER Diagram in database engineering guarantees you to produce high-quality database design to use in database creation, management, and maintenance. An ER model also provides a means for communication.

## What is Git and Git-hub and benefit of using it?

- Git is a version control software, thinking about the efficiency, reliability and compatibility of the maintenance of versions of applications. The purpose is to keepp the track of changes in computer files including coordinating the work that various people do.
- Git-hub is a online repository. It lets you and others work together on projects from anywhere. All is saved on a cloud. <br/><br/>
Regarding the benefits, it makes it easy to contribute to your open source projects, it makes it easier to get excellent documentation, it is a repository that allows your work go get out there in front of the public and it can track changes in your code across versions.

## PYTHON

***Q&A***

- __Question 1: What is Python and benefit of using it?__<br/>
Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive fo Application Development, as well as for use as a scripting or glue language to connect existing components together. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects. So for that reason it supports multiple programming paradigms, including structured, Object-Oriented Programming (OOP) and functional programming. <br/>
The benefit of using it, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance, it supports modules and packages, which encourages program modularity and code re-use. But for the reason that Python is object-oriented, it supports with thousands of libraries that you can use in your own work. Python has an enormous user community. <br/>
Python is a great language for scripting, deployment automation, and web development. This makes it one of the most suitable langauges for DevOps currently. It is highly demanded. Python helps achieve the same through a wide array of libraries and packages, accesibility, and flexibility. So Pyython is a scripting language, and it can be used in many different ways for many different types oj jobs. DevOps and Python is one such rare combination that promises agility, giving us an edge over ours competitors. DevOps and Python makes things simpler and help to transform with the new technologies in the market rigth now.

- __Question 2: What is OOP and why should we use it?__<br/>
Object-Oriented programming (OOP) is a method of structuring a program by building related properties and behaviors into individual objects. Let's have a look at an initial example. Imagine that you have to describe a car to someone who's never seen one before. You may want to start telling that it's a wheeled motor vehicle used for transportation. Also you would like to mention that there are several brands of cars, or some aspects like it has four tires that they carry up to five people. So Computers have no natural thought of what a car is, why were they made or who employments them. And in the event that you need your computer to accurately get it the protest, a car in this case, you have got to clearly clarify which are its attributes and what functions they will do. For that reason Python uses a programming pattern called object-oriented programming, which models concepts using classes and objects. <br/>
It is a flexible, powerful paradign where we can use classes which represent and denife concepts that we want to show to the customers. It makes complex code easier to develop, more relieable, more maintainable and it lets you change the implementation of an object without affecting any other code, so for that reason we should use it.

- __Question 3: The benefits of OOP and best use cases?__<br/>
It is exceptionally valuable for the reason that it permits you to bundle together information states and functionality to alter those information states, whereas keeping the subtle elements hidden away. As a result, code with OOP plan is adaptable, measured, and abstract. So this makes it especially valuable after you make bigger programs. <br/>
The benefits of OOP are:
1. It lets you change the implementation without affecting any other code.
2. It allows you to have different functions with the same name and functionality but on different data.
3. It allows you write generic that will work with a range of data without knowing how it is defined.
4. It lets you write a set of attributes and functions that will expand them in different ways without copying in any way. <br/><br/>
An example of use case we can continue with the same example of the above question. The concept of object-oriented programming comes down to attributes(the characteristics associated to a type) and methods(the functions associated to a type) associated with a type. In the car example, the color and brand are two attribute associated with every car, so we can define this two attributes in the Car class. On the other hand, methods would be actions perfomed by the car, such as driving. So every instance created in the program will have the attributes of `color` and `brand` and the function `driving`.

- __Question 4: What is an API and why should we use it?__<br/>
API is the acronym for Application Programming Interface, that means software intermediary that allows two applications to talk each other within the API. So is a set of programing code that enables data transmission between one software product and another. Let's see a simple example: Imagine that you are in a restaurant, siting at a table with a menu of choices to order. So the kitchen is the part of the system that will prepare your order. But we need something to link the communication between the kitchen and the customer to deliver the food. Here is when the waiter comes in. The waiter will be the messenger (API) that takes your requests and tells the kitchen and then come back with your food. <br/>
The benefits of using API are:
1. Better integration: you can integrate your applications with third parties in order to optimize their functionality and to improve usability.
2. Automating tasks: Thanks to automation and integration of processes your business can save costs, time and efforts.
3. Improved services: APIs simplify the implementation of new applications, business models and digital products and allow an effective complementation with third-party products or services whilst improving their development.
