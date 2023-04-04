#   BOOK STORE
MCA SEM 2 MINI PROJECT
# Submitted By

- JIGYASU SINGH CHOUHAN			
- NAYAN THAKRE
- GAURAV GABA
- CHINMAYA GARNAIK

  # Abstract
•	The project report consists of 2 phases. In the first phase, the problem assigned to us has been mentioned. Second phase provides the solution for the same problem along with an insight into the development process involved.

•	Introduction part gives the information regarding online book shopping. It also gives brief introduction about the project under the topic problem definition .it gives a short introduction about bookshop and its operations.

•	The next part is the requirment analysis which is mainly concerned with study of various requirements such as user, system, hardware/software & performance. It also includes feasibility study of system.

•	The next part is on system design, which include interface design, detailed design.

•	It also includes function flow, dfd, and er diagram & databsse design.

•	Last part is regarding conclusion about above mention problem




   # Introduction:

The online book shopping is to automate all operations in a bookshop. Generally it includes the order processing, stock management and accounts management.
Before automating a bookshop we have to understand the concept of automation. In automation of any operation we make a system which do work automatically as the respective events occurs, for which it is meant.
There are the some common examples of the automation like that auto pilot system in the aircraft, automatic home systems (electric system, water system, fire alarm system, doors system etc). These are best examples of the automation systems.
Here we are try to develop such type system which is provide the automation on the any type of the bookshop. That means a shop which has the type system which provides the facility to the customers of the shop to purchase the books from the shop without any complexity.
For example any customer want to purchase any book from the shop than first of all customer just choose the stream of the book than he/she can see the more then one type of books there and than he/she can choose the specific book from there. And then purchase it by paying price on bookshop cash counter and receives its invoice. 
#Development tool and technology

The System Uses J2ee Environment And Java1.8 As Code Language, Hibernate And Apache Maven As An Extended Frameworks, Back End Side My Sql Database, Development Tool As Eclipse Oxygen, Database Management Tool As Mysql Xampp
Below There Is Some Explanation About These Terminologies. 

# APACHE TOMCAT SERVER 8.0 

The Apache Software Foundation Provides Support For The Apache Community Of Open-Source Software Projects. The Apache Projects Are Characterized By A Collaborative, Consensus Based Development Process, An Open And Pragmatic Software License, And A Desire To Create High Quality Software That Leads The Way In Its Field.  
 
Apache Tomcat Is The Servlet Container That Is Used In The Official Reference Implementation For The Java Servlet And Java Server Pages Technologies. 

# Advantages:--

Performance Optimizations And Reduced Garbage Collection 
Refactored Application Deplorer, With An Optional Standalone Deplorer Allowing Validation And Compilation Of A Web Application Before Putting It In Production. 
Complete Server Monitoring Using Jmx And The Manager Web Application 
Scalability And Reliability Enhancements 
Improved Taglibs Handling, Including Advanced Pooling And Tag Plugins 
Improved Platform Integration, With Native Windows And Unix Wrappers 
Embedding Using (Java Management Extension) Jmx 

# J2EE PLATFORM 

The Java 2 Platform, Enterprise Edition (J2ee), Developed By Sun Microsystems, Is A Platform-Independent Development Environment For Java Based Enterprise Applications. J2ee Provides Support For A Number Of Components Which Extend The Java 2 Platform To Facilitate The Development Of Web-Based Applications; Namely Enterprise 2005)]. 

# SOFTWARE DESIGN PATTERNS: 

Software Design Patterns Are Pre-Defined Solutions To Recurring Problems In Software Engineering. Although Many Patterns Exist Which Can Be Applied To A Wide Range Of Platforms, The Sun Javacenter Has Also Published A Set Of Patterns Relating Specifically To J2ee Development Projects [Alur, Et Al (2003)]. As Winn And Calder (2002) Explain, Adherence To Software Design Patterns Can Significantly Aid The Process Of Development By Providing Expertly Verified Solutions And Accepted Standards For Good Practice.
THE MODEL VIEW CONTROLLER (MVC) PATTERN:

One design pattern which has been adopted across a wide range of software development projects and platforms is the model view controller (mvc) pattern. The main concept behind mvc is the separation of design concerns in application development into three layers – the model, view and controller. The model component manages the business logic and application state, the view renders the model for display to the user and the controller translates interactions with the view into actions performed by the model. Figure 1.1 shows how the mvc layers are connected. 

  
# MVC MODEL

The separation of design concerns through the use of mvc exposes a number of possibilities, including the ability to build a number of alternative view components which utilize the same model and controller. In addition, collaborative developments can be approached with more confidence and ease when the various components have been clearly separated. 
As we mentioned above, j2ee technologies can be combined in order to achieve more effective application designs. In terms of j2ee developments, the mvc design pattern is embodied by the so-called model 2 architecture where java beans are used to represent the model layer, jsp pages for the view and java servlets for the application controller. When a request is sent to a model 2 application, the controller servlet initiates state changes in the model though the instantiation and manipulation of one or more javabeans. At the stage where a response is to be generated, thecontroller servlet selects an appropriate jsp page to supply the view. Figure 1.2 provides a diagrammatic representation of a typical model 2 application. 
![MVC](https://user-images.githubusercontent.com/52603806/227454142-e9c46dca-da7c-4d9a-a811-65d2c29ec134.png)

 
# MVC MODEL 2 APPLICATION

Although The Typical Model 2 Framework Provides An Effective Means Of Decoupling The Mvc Design Concerns; The Controller Component Can Be Criticised For Having A Lack Of Maintainability. Utilising A Collection Of Servlets To Provide The Application Controller Exposes The Opportunity To Reuse Model And View Components For Different Operations. However, This Carries The Drawback Of Having Replicated Code In Each Servlet For Performing Common Controller Operations. The Repercussion Of Replication, More Pertinent In Larger Developments, Is A Reduced Level Of Maintainability - Where More Components Of The Application Will Be Impacted When A Change Needs To Be Made. 

![image](https://user-images.githubusercontent.com/52603806/227454246-ee6f7198-a4ed-42d3-aa48-b53705961e19.png)


# JSP 
Java Server Pages (Jsp) Is A Java Technology That Helps Software Developers Serve Dynamically Generated Web Pages Based On Html, Xml, Or Other Document Types. Jsp Was Designed To Address The Perception That The Java Programming Environment Didn't Provide Developers With Enough Support For The Web. 
Jsp Is A High-End Technology That Helps Developers Insert Java Code In Html Pages By Making Use Of Special Jsp Tags. The Jsp Are Html Pages But Do Not Automatically Have .Html As File Extension. Jsp Files Have .Jsp As Extension. 
The Main Features Of Jsp Technology Are As Follows: 
A Language For Developing Jsp Pages, Which Are Text-Based Documents That Describe How To Process A Request And Construct A Respons 
Business processes of existing system:
During the system study the following types of business processes were identified:

•	Business processes related to store sales
•	Business processes related to inventory management

# Store sales:

•	Customer book searching
•	Book reservation
•	Book purchase – generating invoice, billing the customer and entering sales order.

# Inventory management:

•	Searching inventory - searches bssed on title, code, author and category.
•	Buying books from supplier and adding them to inventory ( also entering the new books details in the databsse).
•	Removing books which are not fast moving or which are damaged and sending them back to supplier

# ther processes (related to manager)
•	Viewing sales records
•	Generating sales summaries
•	Understanding the sales trends
 


# Problems and constraints:
Manual management of any task is time consuming having lots of errors, which will lead to corrupt records in registers. In case of existing management system, authorized person has to face a lot of problems. Few of them are as follows:
•	change of profile’s information of any customer, staff and supplier requires overwriting in existing records every time.

•	in order to delete the record of a particular customer, the person maintaining records will have to search the record of that particular person in every related register.

•	for issuing order, first the product register reference is to be made, which is time consuming process.

•	manual calculation of installment and payment is required, which is error prone.

•	reports are generated manually.

•	searching is quite hectic task for a person.

•	no way to check the different queries which may arise at various stages of processing.

•	if any reference is to be made to any particular register and it is not available, then no further work can be done.

•	While modifying a record, the person will have to first search the record and then make changes of that particular record in every related register.


![image](https://user-images.githubusercontent.com/52603806/227454329-104aea9c-f742-4a92-b70c-c34488485e36.png)

 
 # Requirement specification:

•	From discussion with various bookshop owners various requirements are arrived at:

Book shopping system (bss):
•	bss should help the customers query whether a book in a stock the user can query the availability of a book either by using the book title or by using the name of author.

•	if the book is not currently sold by the bookshop, then the customer is asked to enter the full detail of the book for procurement of the book by the bookshop.

•	the customer can also provide his e-mail address and mobile, so that he can be intimated automatically by the software as and when the book copy received.

•	if a book in stock, the exact number of copies available and the rack number in which the book is located should be displayed.

•	if a book not in the stock, the query for the book is used to increment a request field for the book.

•	the manager can periodically view the request field of the book arrive at a rough estimate regarding the current demand for different books.

•	bss should maintain the price of various books.

•	as soon as customer selects his book for purchase, the sale clerk would enter the isbn number of the books. Bss should update the stock and generate the sales receipt for the book.

•	bss should allow employees to update inventory whenever new supply arrives. Also   upon request by the owner of book shop.

•	bss should generate sales statistics (viz, book name, publisher, isbn number, number of copies sold and the sales revenue) for any period.

•	the sales statistics will help the owner to know the exact business done over any period of time and also determine the inventory level required for various books.

•	the inventory level required for a book is equal to the number of copies of the book sold over a period of one week multiplied by the average number of weeks it takes to procure the book from its publisher.



# Interface requirements:

User interfaces

The system users are:-
•	the book shop management as the system administrators.
•	book shop cashiers as the normal users.

# System administrators

The administrator logs on to the system by inserting administrator user name and password. Administrator can do any transaction as well as editing all details inside the databsse such as adding, editing and deleting a new user or adding, editing and deleting items.
System users

System users are the ones who at the cashier and do transactions with customers. The users have to enter the user name and password and click on ‘login’ button. If user makes any mistake the system will ask for the correct username and password until he enters the correct one.
When the user wants to do any transaction user has to click on the menu icon on the main menu. Then the transaction window will open. User has to enter the book no and press enter. Then user has to select the transaction type and the quantity. Then click on the update button. Then the system will automatically update the database according to the transaction type. Hardware interfaces

# Performance requirements:
•	The response time for menu changes will be not more than 3 seconds.
•	The time for search for a book will not more than 3 seconds.
•	The time to print the stock valuation will not be more than 3 seconds.
•	The time taken to update the database or get information from the database will not be more than 2 seconds.

# Design constraints:
•	the system is based on menu driven interfaces. Menu selection will be done by using the mouse and the key board keys.
•	confirmation messages on taken actions, input acceptance and error conditions will be displayed after each input.
•	error messages will be displayed at the time of detection of input errors and the system errors. 
#Problems are solved by system:
Here our main goal is that we are just solving the problem of selling of book in the particular very big book shop which have large amount of books within it. Since there are many people would be in the shop to provide the good service to the customers of the book shop. But it is not possible to provide the good service to the customers because it is not possible by the manually. There are the some problems which may be solving by our application. Which are as follows:-
•	Fast service: - in the sense of fast service by this we can give the fast service (entertain, selling, purchasing, money deposits etc.) To the customers of the shop.

•	Reduces the workload: - in the sense of workload reduction that means all the tasks are done by the automated system/machine which give the rest to the shop owner.

•	Good management: - in the sense of good management our system provide the good management in the book keeping and provide the good scheduling in the all the operations of the book shop.

•	Provide the satisfaction to the customers: - in the sense of satisfaction of the customer, because customer is doing its all operations with the system on his requirements and he is completely satisfied because our system is fulfils its all requirements.

 
# Characteristics of the entities are used to solve the problem:
Here we are use the big one entity which is our computer system. Which is use to run our project in the network environment. So we are use all the characteristics of the computer system to solve the problem all the problems which are occurs in book shops operations. There are the some characteristics which are as follows:-
•	Fast accessibility: - by any computer system we can got the fast access for our operations.
o	Which are take the more time in the manually form.

•	Multitasking: - by this character we can perform the more than on task at single time.

•	Storage space and management: - by this character we have the large space to have all the records which are completely safe and sound in compare to the manually management.

•	Portability: - by this we can remove the problem of state of the customer that means customer can access all the operations from any place on its facility.

•	Mobility: - by this we can remove the problem of specific place and time. Which is always needed in manually system? Because our project is able to survive in the network environment.

•	User friendly environment: – graphical user interface is used for easy handling of the system. A user can use the system efficiently without meeting any difficulty.

•	User satisfaction: - under consideration according user requirement and expectation, the system is developed.

•	Security: - system is secure in itself by checking the illegal access of invalid users. System is also capable to input some security checks at certain points

•	Quick response: - as the processing time of any task is minimized therefore the user gets the quick response of his/her queries even though there is a huge amount of data.

•	Robust error handling: - the errors and undesirable situation, generated through the user intervention, are handled successfully to ensure that the system operates without halting by providing the appropriate error messages to the user.

•	Accuracy: - all the processes provided by the system are accurate thus increase the reliability.
 
# System design:
Procedural design:


![image](https://user-images.githubusercontent.com/52603806/227454424-7a730735-65e0-4b5d-b690-d29ea052eab9.png)

# Detail data flow diagram (DFD):

![image](https://user-images.githubusercontent.com/52603806/227454575-d59535d3-6b80-46f8-be98-925c82d56110.png)


# screenshot of project

# index
![Screenshot 2023-04-04 090441](https://user-images.githubusercontent.com/52603806/229680890-6a3110de-8230-4e5e-8830-22a294c2f5a9.png)
# Customer
![Screenshot 2023-04-04 090631](https://user-images.githubusercontent.com/52603806/229680965-ab7a6454-60a6-4682-aec5-74e9f5c00e12.png)
# Admin![Screenshot 2023-04-04 090746](https://user-images.githubusercontent.com/52603806/229681088-bb1aa1a3-99b1-41fc-86e5-1a02a29285b8.png)

