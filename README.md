# onlinoexamino
online examination system
Chapter 1				SYNOPSIS


Online Collaboration System

The “Online Collaboration System” is a site devoted to making it easier around the world to work together. It will help a team of persons in setting up a frontline information system for sharing information among each other across all interface units. The Online Collaboration System is nothing but the electronic counter part of Team Work. It will not replace the traditional channels of communication, such as phone or fax, but will act as just another extension for the group of persons to work in a single project / task interacting with each other in one-to-one basis. It will be more personalized and interactive across both electronic as well as traditional channels.

This project can also be named as online teamwork Network System. This application at present will provide five major features: Messaging, Team Management, File sharing, Discussion Forums and Project tracking.


EXISTING SYSTEM

      At present we don’t have a sophisticated electronic collaboration system to work electronically in a group. Sometimes we need to do a project by hiring some specialist from other places. Instead of hiring people to do jobs, we add people as needed to perform certain tasks.  Sometimes we may need to work with a client on a project, and after finishing that particular project we all go our separate ways. If we need help doing something, we bring people in to do those tasks. For all these we use emailing, file attachment or some other sources of communication. The problem with all these collaboration however is the sheer number of places information can get lost. We might have some information in our email program, some printed on paper on our desk, some files stored on various computers, and lots of phone calls, for which there is really no record. We don’t have a central repository of information.

           Hence, an application is needed that should provide file sharing, project tracking, discussion forums, Messaging and an overall infrastructure supporting additional subsystems in future. 


PROPOSED SYSTEM

    The Proposed system is a central repository for all the information of a particular user. It provides file sharing, Messaging, an efficient team management and an overall infrastructure supporting additional subsystems in future. This application software keeps track of each member of the team, his messages, files etc.




Software modules of Online Collaboration System: -
At present the proposed Online Collaboration System has three modules. The modules are –

•	Team Management.
I.	Team Creation Module.
II.	Viewing Team Members.
III.	Adding Team Members.
IV.	Deleting Team Members.

•	Messaging System.
I.	Viewing Massages.
II.	Sending Massages.
III.	Reading Massages.
IV.	Deleting Massage.
V.	Emailing

•	File Library
I.	Uploading and Downloading Files
II.	Folder Creation 


This System is developed using the following software platform: -

	Windows XP as the O.S.

	SQL Server 8 as the database.

	ASP.NET with c# as the development language.















CHAPTER 2			        INTRODUTION

   
Online Collaboration System

             Just take a moment, sit back and imagine being able to control all your work from the privacy of your own home or office. Sitting in front of a computer, with one click of the mouse you can just share the files, Send instant messages to your team member. Might be saying to yourself, this is good to be true and it must be some type of mirage, but it is not. Welcome to the new age of working, which is called Online Collaboration System. 

         One of the more interesting aspects of the Internet is how it has made virtual corporations a reality. Instead of hiring people to do jobs, we add people as needed to perform certain tasks. This is essentially true among independent contractors. Sometimes we may need to work with a client on a project, and after finishing that particular project we all go our separate ways. If we need help doing something, we bring people in to do those tasks. The problem with all these collaboration however is the sheer number of places information can get lost. We might have some information in our email program, some printed on paper on our desk, some files stored on various computers, and lots of phone calls, for which there is really no record.

          This is where this ONLINE COLLABORATION SYSTEM steps in. It will help a team of persons in setting up a frontline information system for sharing information among each other across all interface units. The Online Collaboration System is nothing but the electronic counter part of Team Work. It will not replace the traditional channels of communication, such as phone or fax, but will act as just another extension for the group of persons to work in a single project / task interacting with each other in one-to-one basis. It will be more personalized and interactive across both electronic as well as traditional channels.

         This project can also be named as online teamwork Network System. This application will provide five major features: Messaging, Team Management, File sharing, Discussion Forums and Project tracking.

       These five subsystems are integrated in a complex infrastructure, out of which I have build the three modules. Besides the five major subsystems, a user login system, a sign up system, and a add member system will also be implemented .A customized home page will consolidate information from the five subsystems onto a single page for the user, and a search utility will enable the user to search for content in all the subsystems.

       Online Collaboration System is a site devoted to making easier for teams around the world to work together. 

 



 
LITRATURE REFERENCE:


This topic gives the details of literature survey done during the project period.

Normally all system follows same life cycle i.e. design, development, implementation and maintenance phase. The system life cycle stated by 
Elias M. Awad and Rajiv Mall  has been referred during the project work. This book has also explained the phases of the system development life cycle and various tools and techniques used during these phases.

                   Requirement determination is a vital phase of system development life cycle. Any mistake or ignorance in requirement determination can lead to implementation problem. By going through various literatures related to functioning of users, like interaction with the users, we get the idea of the various requirements of users.

Feasibility study is the most important for any system, which justify the new system as a perfect substitute for any existing system. There are various areas in which feasibility is to be determined like Economical, Behavioral and Technical. Portions enumerated by Awad are used for the same.

                     Data Flow Diagram is a powerful tool for system analysis. DFD gives overall picture of the system and flow of data, which can also be understandable to the user of the system and may help in improving the system. DFD has been drawn according to the book of Awad and Rajiv Mall, for the system that includes processes, files or data stores and data flow of the system.

For designing an interactive user-friendly system, a good input/ output screen design is required. For this purpose Elias M. Awad’s concept is used for structuring and designing input/output screens.

                            Any new system should be completely checked and tested before implementation. Any bug remained in the implemented system may cause serious problem. Steps defined for testing a system in various stages by Awad and Rajiv Mall has been very useful for testing the system.

For installing and implementing the system, it is required to know the security provided by the system i.e the source code should be protected from possible unauthorized use or modification. For these the component based programming has been done where I have creatd  “.dll”  files  which cannot be modified by user’s.

                         Relational database has been proved to be most successful Database Management System. Database concept by Korth and C.J. Date; have been extensively studied in order to understand the concept and capabilities of RDBMS.


     
 
    
 Chapter 3		               SYSTEM ANALYSIS


3.1 OVERVIEW  OF  THE  EXISTING  SYSTEM

          At present we don’t have a sophisticated electronic collaboration system to work electronically in a group. Sometimes we need to do a project by hiring some specialist from other places. Instead of hiring people to do jobs, we add people as needed to perform certain tasks.  Sometimes we may need to work with a client on a project, and after finishing that particular project we all go our separate ways. If we need help doing something, we bring people in to do those tasks. For all these we use emailing, file attachment or some other sources of communication. The problem with all these collaboration however is the sheer number of places information can get lost. We might have some information in our email program, some printed on paper on our desk, some files stored on various computers, and lots of phone calls, for which there is really no record.


3.1.1 LOOPHOLES  OF  EXISTING  SYSTEM

        However at present there are very few sites available for online teamwork and whichever sites available don’t have much flexibility and moreover costly too. Due to that people use emailing , file attachments and some other source of communication which are not much flexible. Some of the drawbacks of the present systems are :-

	Total process (team working) takes a lot of time. Moreover information can get lost since some of the information may be printed on paper on our desk, some files stored on various computers, some may be in email and lots of phone calls, for which there is really no record.

	Since all the information’s are scattered so the files may get lost and result in lose of important information.

	If we are going to do the teamwork through the available website it cost a lot to the user which restricts them use those.  

	While we can attach file to an email and send them to someone, this is not always the most practical solution. Some time we hate dealing with email since we often get large attachment that take forever to download. We also get several copies of the same attachment from different people on the same team, just to make sure that we got the copy. There are also problem with the sites that do not allow attachment or that limit the size of them due to bandwidth reasons. Further more, there is a inevitable problem of forgetting where we put a file that someone sent us and having to bother that person again to get a new copy.

	There are few sites which deals with online collaboration system. But these sites are very complex, hard to learn and hard to use. These collaboration solutions contains full of features that rarely get used and get in the way of effective collaboration. 


3.2 PROBLEM DEFINATION: -

          Too many messaging systems cause you misplace or lose of information and not have a reliable way to share knowledge generated through email conversations. Moreover, teams spread out often don’t have a central location for depositing their files and messages.


3.3 OBJECTIVE OF PROPOSED SYSTEM

      An ASP.NET application that provides file sharing, project tracking, discussion forums, Messaging and an overall infrastructure supporting additional subsystems in future. This application software keeps track of each member of the team , his messages, files etc.

     Some other objectives are: -
	It should be simple. Simple to set up, simple to learn and simple to use. 
	Making it easy to find people and information. You can organize information by people, topics, etc. 
	Collaboration isn't always about big teams. It's just as important to small teams and individuals. It stops you from doing the same thing twice, and you don't have information sitting in multiple places. 
	Online Collaboration System simple and powerful. It should make online collaboration faster and easier. It should able to use effectively by computer novices and experts.  
	Information should be secure.












3.4 FEASIBILITY ANALYSIS

               After making the initial investigation, feasibility study is carried out to check the workability of the system. Feasibility study is the vital step in the system development life cycle. It is the test of a system proposal according to its workability; its impacts on the organization’s ability to meet the user’s needs and effective use of resources. During this study, the problem definition is centralized and the aspect of the problem to be included in the system is determined. Consequently cost and benefit are estimated with greater accuracy at this stage.

            The result of the feasibility study is a formal proposal, which is simply a report, a formal document detailing the nature and the scope of the proposed solution. The proposal summarizes what is known and what is going to be done. 

           Three key consideration are involved in the feasibility study:
•	Economic feasibility 
•	Technical feasibility
•	Behavioral feasibility
•	

3.4.1	Economic feasibility

Economic feasibility concerns returns from investments in a project. It determines whether it is worthwhile to invest the money in the proposed project or whether something else should be done with it. Economic feasibility also known as cost and benefit analysis, the benefits and advantages of the candidate system are compared with cost. If the benefit outweighs the cost, then the decision is made to design and implements the system. Benefits can be seen in terms of efficiency, productivity, error free decisions, rendering data to others projects, queries etc.

        The proposed system is economically very feasible because all the information maintenance that is file, messages etc are maintained by the system. Moreover if somebody need the help of someone who is not there at present then he need not call him to its place .He or she can work from any where across the world. 

Minimum equipments are required to develop the system. No one is required to maintain the system. The member who wants to work through the system will manage their team themselves.

However, the developer of the system can earn money by taking minimum fees from the member who wants to use the system.

Hence, we can conclude that the proposed system is economically feasible.







3.4.2 Technical feasibility

Technical feasibility checks whether the proposed system is technically feasible or not. It involves financially consideration to accommodate technical enhancement. The minimum requirement of hardware resources to develop the system is sql server 7. 0 or above and .NET framework. The resources required in the user side are the only browsers.

           Technical issues involved are the necessary technology existence, technical guarantees of accuracy, reliability, ease of access, data security, aspects of future expansion.

i.	Technology exists to develop a system.
ii.	The proposed system is capable of holding data to be used.
iii.	The proposed system is capable of providing adequate response and regardless of the number of users.
iv.	The proposed system being modular, if the developer wants can add more features in the future and as well as be able to expand the system.
v.	As far as the hardware and software is concerned, the proposed system is completely liable with proper backup and security.

                Since the proposed system is built in the .NET framework, it is platform independent. So we can execute the proposed system in any of the operating system.


3.4.3 Operational Feasibility

           If the system meets the requirements of the customers and the administrator we can say that the system is operationally feasible.
      
                     The proposed system will be beneficial only if it can be turned into a system, which will meet the requirements of the online team work when it is developed and installed, and there is sufficient support from the users.
      
i.	The proposed system will improve the total performance.
ii.	Team members here are the most important part of the system and the proposed system will provide them with a convenient mode of operation for them.
iii.	The proposed system will be available for the teams for working online throughout the globe.
iv.	The proposed system will provide a better messaging system to the members.

Hence, the proposed system is operationally feasible.



3.5  Requirement Analysis and Specification
Before starting to design a software product, it is extremely important to understand the precise requirements of the customer and to document them properly. Improper documented requirements increase the number of iterative changes required during the life cycle phases. Therefore, requirement analysis and specification is considered to be a very important phase of software development and has to be undertaken with utmost care.

           The requirement analysis and specification phase starts once the feasibility study phase is complete and the project is found to be financially sound and technically feasible.

This phase consists of following two activities: -

•	Requirement gathering and analysis
•	Requirement specification


3.5.1	REQUIREMENT GATHERING

               For requirement gathering for the proposed system “Online Collaboration System” I have used the following requirement gathering techniques technique: -

•	Asking: - Asking strategy has been most frequently used while developing the system. I have got a lot of knowledge regarding the user requirement through asking.
•	Deriving information from existing system: - I have gone through all the communication technologies available in the present day. Also I have gone through the number of site to collect the information regarding the proposed system.

Through requirement gathering I tried to get the answer for the following question: -

•	What the problem is?
•	Why is it important to solve the problem?
•	What are the possible solutions to the problem?
•	What exactly are the data input and data output required for the system?
•	What are the likely complexities that might arise while solving the problem?











3.5.2	ANALYSIS OF GATHERED REQUIREMENT: -

                  The main purpose of this activity is to clearly understand the exact requirements of the user of the system. By analyzing the gathered information I came to the following conclusion: -

•	Too many messaging systems cause misplace or lose of information and we don’t have a reliable way to share knowledge generated through email conversations. Moreover, teams spread out often don’t have a central location for depositing their files and messages.

•	The possible solution is An ASP.NET application that provides file sharing, project tracking, discussion forums, Messaging and an overall infrastructure supporting additional subsystems in future. This application software keeps track of each member of the team, his messages, files etc.


3.6	SOFTWARE REQUIREMENT SPECIFICATION (SRS)

          After collecting all the required information regarding the software to be developed I made the SRS document. The SRS document usually contains all the user requirements in an informal form.

1. Introduction: -

a)	Background and overall description: -

                The proposed system has been developed in order to build the electronic counterpart of teamwork. And also to help team member to keep their important messages, files, etc at one place so that they can be available whenever needed.

b)	Environmental characteristics: -

i)	Hardware: - For developing the proposed system the hardware requirement at the minimum will be 10gb hard disk and 64 mb RAM but for better performance higher configuration is suggested.

ii)	Client side requirement: - For using the proposed system the browser is the basic requirement.  

iii)	People: - Since the proposed system basically deals with working online in a team. So the people interacting with the system will be at least a internet knowing person. Hence the system has to be developed by keeping that in mind and since the user will be internet knowing person the task of developing become little easy.


       2.Goals of implementation: -

The proposed system should be built in such a way that it should fulfill the following goals: -

I.	The code should be easily manageable.
 
II.	The code should be reusable.

III.	The performance rate should be higher. It should be fast.


      3. Functional Requirements: -The system contains following functional requirement: -

I.	Creating a team.
II.	Adding a member to team.
III.	Team management.
IV.	Sending and receiving messages.
V.	File sharing.
















3.7 Context Diagram of the Online Collaboration System
        The system to be developing is for Online working together in a team. There will be a team leader for every team. He will manage the whole team. The team member can exchange messages and emails regarding the project they are dealing with. The teams can also upload and download files. The user first logs into the system and performs action as per the permission given to them.

The following diagram describes the working of the proposed system: -

   
                                   

                                    	     Query responses




				Team management queries



				   Messaging queries






				Query responses

                Context Diagram Of The Online Collaboration System







3.8 Development Strategy: -

       Online Collaboration System is designed using ‘The waterfall model’. The waterfall model was the first structured approach to systems development. The waterfall model is just a time-ordered list of activities to be performed to obtain an IT system.


























        Fig.- System development Life Cycle of Online Collaboration System

The activities in waterfall model are: -

System Analysis: The step refers to the gathering of system requirements, with the goal of determining how this requirement will be integrated in the system. Extensive communication between the customer and the development team is essential. During System Analysis Feasibility Studies are also carried.

System Design: Once the requirements have been collected and analyzed, it is necessary to identify in detail how the system will be constructed to perform the necessary tasks. More specifically, the system design phase is focused on the data requirement (what is processed by the system), the software construction (how will the 

Application be constructed) and the interface design and coding (what will the system look like?)

Coding: Also known as programming, this step involves the system software. Requirement and system specification are translated into computer code. Computer programs are written using a conventional programming language or an application generator. Programming tools like Compilers, Interpreter, Debuggers are used to generate the code. Different high level programming language like C, C++, Pascal, Java, C# are used for coding. With respect to the type of application, the right programming language is chosen.

Testing: As the software is created and added to the developing system, testing is performed to ensure that it is working correctly and efficiently. Testing is generally focused on two areas, internal efficiency and external effectiveness. The goal of external effectiveness testing is to verify that the software is functioning according to system design, and that it is performing all the required functions. The goal of internal testing is to make sure that the computer code is efficient, standardized, and well documented.

Implementation: After the code is tested, if it meets all the system requirements, it is handed over to the customer.

Maintenance: Inevitably the system will need maintenance. Software will definitely undergo change once it is delivered to the customer. Change could happen because of some unexpected input values into the system. The change in the system could directly affect the software operations. The software should be developed to accommodate changes that could happen during the post implementation period.




















Chapter 4

TECHNOLOGY USED IN ONLINE COLLABORATION SYSEM

4.1 .NET

The .NET consists almost all the feature of J2EE. A short comparison between J2EE and  .NET is given below: -


Feature                              .NET Framework                        J2EE Framework


Component                      .NET, COM+                                 EJB,JavaBeans
Architecture

DataBase Access             ADO.NET                                     JDBC

Wb Page Generation        ASP.NET                                      JSP, and servlets

Language                         Multiple Language                        Java

Platform                            Windows(going to be                   Multiple
                                           Multiple )



4.1.1 .NET Development basics

          The application types that can be developed with .NET include: -

	Class Library
	Console Application
	Windows Application
	ASP.NET Web Application
	ASP.NET Web Service
	Windows Service

     The proposed application is the ASP.NET Web application.

4.1.2 Language supported by .NET

 There are potentially over two dozen languages that .NET supports. Some of   them are: -

	C# .NET
	VB .NET
	C++ .NET
	J# .NET
	COBOL for Microsoft .NET
	Python for Microsoft .NET
	Pascal for Microsoft .NET
	SmallTalk for Microsoft .NET 
	Perl for Microsoft .NET and many more.

     The language used for the proposed system is C# .NET.


4.2 ASP.NET

                  ASP.NET is a new Internet programming technology from Microsoft that applies a more streamlined and interspersed with client HTML. ASP.NET is more than the next version of Active Server Pages (ASP); it is a unified Web development platform that provides the services necessary for developers to build enterprise-class Web applications. While ASP.NET is largely syntax compatible with ASP, it also provides a new programming model and infrastructure for more secure, scalable, and stable applications. 
          ASP.NET is a compiled, .NET-based environment; Applications can be developed in any .NET compatible language, including Visual Basic .NET, C#, and JScript .NET. Additionally, the entire .NET Framework is available to any ASP.NET application. Developers can easily access the benefits of these technologies, which include the managed common language runtime environment, type safety, inheritance, and so on.

4.2.2 Why ASP.NET: -

      We can say that ASP.NET is the latest version of ASP  yet there is no programming similarity between ASP and ASP.NET. With ASP.NET, developers no longer need to paste together a jumble of HTML and script code in order to   program  the web. 
     
        There are many more advantages of ASP.NET.

        Draw Backs of Existing server side application technology and advantages of           ASP.NET over those.






	Scripting Limitation: 

The existing web technology is limited with the scripting language. For instance ASP can be programmed only in VB Script and Java script. In ASP.Net web pages are developed and designed in a modern .NET language, not in scripting language.

	No application structure: 

ASP code is inserted directly into a web page along with the HTML. Since HTML is not at all an object oriented language .As a result web form code can rarely be reused or modified without hour’s effort.

	Headaches with deploying and configuration: 

If we want to update a component in ASP or in any other existing sever side tech.    We need to manually stop and restart the server. But it is not in the case of ASP.NET.


	Not browser specific: 

             ASP.NET is a browser independent programming model.

	The validation of the controls has become very easy with ASP.NET .It has many in built Validation Controls.

          Language supported by the ASP.NET: 
                 
At present it supports following languages but more languages will be added in near future: -

	Visual Basic .NET
	Visual c++ .Net
	Jscript .Net
	C# .Net 



4.2.3 Why C-Sharp(C#): -

The language I have chosen for developing the proposed system is C-sharp. NET. C# is a modern object oriented language consisting the power of C, C++ and JAVA and the flexibility of Visual Basic.

         The language C# is closely related to c++ but having a lot of extra feature. The language c# and java are mostly equal from a feature standpoint. But In a pure Windows environment, it is hoped that c# running inside the .NET Framework will out-perform Java and it is hoped that c# will also be more reliable.






4.3 DATA ACCESS TECHNOLOGY


      The data access technology used in ASP.NET is the ADO.NET. It is the technology that the ASP.NET is applications use to communicate with the database. 

       The ADO.NET has got a lot more advantages over the classic versions of ADO(data access technology used with ASP).  ADO.NET is made up of collection of objects. Some of which are entirely new, and others of which have evolved from ADO. The five main object types used in the proposed system are given below: -


1.Connection Object: This object is the route through which all instruction to the data store are sent.

2.Command Object: Command object contains the instructions that specify what information should be sent to the database.

3.Data Reader         :This object is used for reading the data. It can read the data in  forward only direction.

4.Data Adapter Object: This object represents a set of commands and a database connection, providing an alternative method of retrieving data.

5. Dataset Object: This object can be thought as a local copy of a portion of the data store. In this copy, rows of data can be read , added, edited and deleted.















Technology involve in data access is shone below: -


        
                                                        Database





					  
                                                 
                                                   Data Access Layer










Application
















4.4 INTERNET INFORMATION SERVICES (IIS)

Internet Information Services (IIS) 5.1 for Microsoft Windows XP Professional brings the power of Web computing to Windows. With IIS, we can easily share files and printers, or we can create applications to securely publish information on the Web to improve the way our organization shares information. IIS is a secure platform for building and deploying e-commerce solutions and mission-critical applications to the Web. 
Using Windows XP Professional with IIS installed, provides a personal and development operating system that allows us to: 
•	Set up a personal Web server 
•	Share information within our team 
•	Access databases 
•	Develop an enterprise intranet 
•	Develop applications for the Web. 
IIS integrates proven Internet standards with Windows, so that using the Web does not mean having to start over and learn new ways to publish, manage, or develop content. 
























Chapter 5

             SYSTEM DEVELOPMENT ENVIRONMENT

The minimum requirement of Hardware and Software for the Online Collaboration System are specified below: -

5.1	 Hardware Requirements

System                             :   IBM compatible PC’s

Processor                          :   P-III

RAM                                 :   128 MB RAM

HDD                                 :   5 GB 


5.2	Software Requirements

OS                                    :  Windows NT, Windows 2000, or Windows XP

Language used                   :   C# with .NET Framework

Compiler                            :   .NET

Database                           :   SQL Server 2000

Markup language                :   HTML with ASP.NET Server controls

Server                               :   IIS

Editor                                :   Notepad or Visual Studio .NET

Browser                             :   Internet Explorer




Chapter 6          SYSTEM DESIGN AND CODING


            The design process translates requirements into a representation of the software that can be assessed for quality before coding begins. Once the requirements have been collected and analysed, it is necessary to identify in detail how the system will be constructed to perform the necessary tasks. The design activity is often divided into two separate phases. One is system design and the other is detailed design.


System design: - System design aims to identify the modules that should be in a system, the specification of this modules and how they interact with each other to produce the desired result. System design describes what component are needed.


Detail Design: -  During detail design the internal logic of the modules specified in system design is decided. Detail design focuses on designing the logic of each of the modules. Detail design describes how the components identified during system design can implemented on software.



6.1 SYSTEM DESIGN


THE Online Collaboration System has at present five modules. The following system design documents focuses detail on these modules and the specification of these modules.

The software modules of the Online Collaboration System are –


•	Team Management.
I.	Team Creation Module.
II.	Viewing Team Members.
III.	Adding Team Members.
IV.	Deleting Team Members.

•	Messaging System.
I.	Viewing Massages.
II.	Sending Massages.
III.	Reading Massages.
IV.	Deleting Massage.
V.	Emailing

•	File Library
I.	Uploading and Downloading Files
II.	Folder Creation 

    Whenever a user will login he will get a homepage specially designed for him, which will contain all the short details such as No. of unread messages, Link for his team, etc. 


1. Team Management Module: 

A team is a group of members selected by a member (known as the leader) to work together. Teams are used throughout the site to group files, massaging etc. We’ll have pages to view to a member’s teams, add, modify, and delete teams, as well as manage the people on the teams. The first page we’ll start with is the team viewer, showing the teams that a particular member leads.

                 Initially, the site will be free to use, but the user should be a member of a team. The user at the time of team creation will sign up. He will be regarded as a team leader and he will only be allowed to add member to his team. Only minimum information is required to create an account and the member will have the ability to make his or her information public, available to his or her teammates, or completely private.

		One team leader can handle only one team at a time. If he wants to work on other team he needs to sign up with other user ID. The team leader will work as an administrator of the team.  He will have the certain extra facility such as: -

	Team Delete
	Team Member Delete
	Add New Member to the Team
	Change the Team Leader


 2. Messaging System Module: -

                  The messaging system built into this application is designed to let members communicate and be informed about what is going on in the system. When members are added and remove from teams, the members in question will be notified through this system. The system can also be used to send team members messages and so on. Most of the work will be done in the Massage object, but I have to build the web pages supporting the logical functions.

                   The members can send the messages as private, public or viewable to the team member only. 

Emailing is also extensively used in the system. Whenever the team leader will add a member to the team then automatically a mail will be send to the added member giving him his user id, Team id and password with a short message from the administrator informing the concerned user that he has been added to his team. The team members can send email to each other.




3. File Library: 

While we can attach file to an email and send them to someone, this is not always the most practical solution. Some time we hate dealing with email since we often get large attachment that take forever to download. We also get several copies of the same attachment from different people on the same team, just to make sure that we got the copy. There are also problem with the sites that do not allow attachment or that limit the size of them due to bandwidth reasons. Further more, there is a inevitable problem of forgetting where we put a file that someone sent us and having to bother that person again to get a new copy.

                The solution to the above problem has been built in this project. This project can be used to upload files and folder to the web server, store them in a virtual folder and allow other user on the team to download the file. We can keep the extensive notes on each file we post. The creator can only delete the files and folder uploaded only.

  Some of the small modules such as Login, Profile Visible are also built into the system.

 More modules such as Discussion Board and Project Tracking will be added in future.

















 Context Diagram of the Online Collaboration System
 Before making the detailed design of a system, first the most abstract representation of the problem is work out. The most abstract representation of the problem is also called Context Diagram.


The following diagram describes the working of the proposed system: -

   
                                   

                                    	     Query responses




				Team management queries



				   Messaging queries






				Query responses

               
              Context Diagram Of The Online Collaboration System










6.2 DETAILED DESIGN


             During detail design the internal logic of each of the modules specified in system   design is decided. The main aim of the detail design is to explain how the system work or how the flow of data takes place within the system. Detail Design deals with system specification.


6.2.1 DATA FLOW DIAGRAM


      The DFD is a simple graphical formalization that can be used to represent a system in terms of the input data to the system, various processing carried out on these data, and the output data generated by the system. The DFD represents the flow of data between the different processes within the system. It is a graph showing the flow of data values from their sources in objects and processes that transform them to their destinations in other objects.

			A Data Flow Diagram consists of processes that transform data, data flows that move data, actor object that produce and consume data, and data store object that store data passively.


	Symbol							Meaning

     
							       External Entity


  
   
							       Process




                                             Data  Store
			     				         
		        

   
   							      Data Flow



Level 1 DFD


								   
								       Teams

								       Project info &
								        Leader ID
									    User Name/Team ID/PWD
										 
				User & Project info			     Leader	   		
									     Info	               Members	  	
										     	
									 	                    Member
								         Leader ID	        Info

				Leader ID 			    Leader
								        ID



									                        Member 
		     Member							                  ID
		        ID		         Member ID
							         Teams
								
										       Team ID &
										       Member ID
    
   
   User	       Member								TeamMember
   Name       ID
  
         Members									
				  Member ID					 DATABASE



       				     User Name,Password



*  T.L: - Team Leader
    T.M: - Team Member



Level 2 DFD of process 1.0


						                                       Members		                      
						   Valid			
						    User	      			      
				                               Data       
      								             			
        User / project Info		           Valid Data         			 Project
									  Info

								                                     
			         		                                                                

		                                              Team ID, Member ID, Password                 Project  &
										           Leader Info
                                                                    		          	

				User Name/Team ID/PWD	



       										       Project          Team
											          Info             ID

Level 2 DFD of process 2.0								             Teams
				
					
                                                                Members				      
                                            
			          	        
			                   User       Member												      Name      ID

						                   User	
                   Login Info	                     	                              Query                               



							        
							    

                        
								      




Label 2 DFD for process 4   //for managing he has to extract all the team members ids

							   
									
									  Team ID	                                             Team ID                      		 Member					TeamMember
					    ID			           Member ID			



		      Leader       Team 				       Member ID
		       ID		  ID					
									
			    Teams 

                               
						        DATABASE
			
		   					
									     
Label 3 DFD For Process 4.3

					
				             Members
							     
									

                       Member ID							    TeamMembers
							       		               

							      
							    

         		Team ID
							                                             Teams

							      

							      
		Team ID							      Members
                         
							                                             


            		Team ID							     DATABASE


	             						                   
       
							      		         
Lavel 4 DFD Of Process 4.3.1




           							               	      
				      		
				       Member ID,	
Member ID			        Email ID			 Email ID		       Deleted User



					                        Member ID	

				
             	                                       Email ID                           
							     Members 
					
			          Member ID





Level 4 DFD Of Process 4.3.2




  Team ID										Teams


								    New Info		      Teams Info














Lavel 4 DFD For Process 4.3.4





					               

            	                						          

Team ID			            Team/Members IDs   
											     Messages

   Team ID



											         Files
				          Team/Member ID’s				          	
         Member ID											      	
											       Folders
									       
 TeamMember               Member ID’s

 				      					
					
 Member ID  			              Team ID
											       Teams    




								
									    









Label 2 DFD for process 5


			Leader ID
					         Teams


			       Team ID



   Leader ID




		           Team ID &      Valid                      User
		            User Info     Data                           Info



			    





					        User Info           Member ID

		        
			      User Name
						     Members


			     					                     Team ID, Member ID
			      User Name								


					          Team ID, Password




									      

									       Team ID, Member ID

								                         
										TeamMembers


Label 2 DFD for process 7.0

		  Messages



						
						    

		Login Name


                   
		       File statistics				Uploaded file
							       
										  File directory in the server
	        File
								   Downloaded file		                
		  File statistics
						
        		    Team ID

             							          Team/folder ID
	      	File statistics							                         Folder
               			                                         	Folder Statistics			 
                          										  
	 Folder ID
              
                          																         		
                      		    Folder ID					folder info			

            
	          	
                           Folder Name



                   File/Folder ID


             



		Email ID






Label 3 DFD for process 7.1





										Message Text
									
	                            Members								      
					                          		      
                                          					               	    Member/Team ID
				                 Member/Team ID
										
                         Login                 			                         	    
                  Name	       
	                          Member
                                      ID                   
login			                                                   Reciever’s ID/           	                Reciever/
                         name					        User Name				     Sender ID
                                                                                      	               		     		 Messages                                                                      
 												            


         

     	              				                    		      
	                                                		                          		
                                                                                                
									
         Member  
        ID	                Team ID
				         
					   Member ID  			       Message ID
TeamMember
















Label 4 DFD for process 7.1.3







			            
                  Member ID	   		         Member ID
          
					 		                     




       Team ID	             		             	                      
					Team ID					         	
							                     

					



         “Public”	               		                                           
					   “Public”
							                      			        Messages	

					













Label 4 DFD for process 7.1.4

									     Confirmation
Reciever’s			  
User name			 Reciever’s ID    	                             
									     Message Info
                      


   User Name	               Receiver’s   						                 Messages
                                        Member ID
           	        			   		      				

	              Members
	

	  Team ID/Member ID						      Message Info
						      		      
	     					
									       
                



Label 5 DFD for process 7.1.4.3


         		               			         				 Reciever’s &
					                      				  Sender’s ID	
         				  Member ID
     


									
  Team/Member ID/									Team &
	  “Public”				    Team ID			           Sender’s ID
					  					 	            Messages
         			        			   				       
											     

     
         	      
										   “Public” &
										    Sender’s ID
				“Public”

						          

Label 3 DFD for process 7.2  
                          

					 
            
		     Browsed files					  File		     
      		       						     
         			          	                             



					       File Statistics
 
				                Files					                    File Directory in Server


				   File ID       	File Name		       


                     File ID										        Downloaded File
									File Name
									    




Lavel 4 DFD Of Process 7.2.1
							                        	   
            											 
					
              

Browsed File Path 			File				  File

		             					   


										          File Statistics


			File having random name	
									     File Statistics
											

	      File Directory in Server							Files





Label 4 DFD for process 7.2.2





		             		    			        			          File Directory in Server
	              File ID							                                                       
												 	      File
									           
											
						           File ID				
										          File Name
			           File ID       File Name		  			                     


                              
		      Files

	  										               


Label 3 DFD for process 7.3
								   
                                               
			        Team ID
											

								         

				        Team ID		
										
							   Folder
								    
					        Team Id=0		            Folder Statistics
											            Files

Team ID/Folder ID  			   Folder ID				
										  Team Id=0

										File Statistics





					Folder ID						   Folder ID

								
											    File Statistics

Label 3 DFD for process 7.3.2



				           Teams				             Files


			          Team ID	       Team Name                    Team ID	       File Statistics

                    					
		Team ID				Team ID





						    Folder Statistics				    
				    Team ID						     File Statistics



								      Folder
									Statistics


Label 3 DFD for process 7.3.4



					Folder ID
								       Folders
		   

						Folder Name
       Folder ID





						         Folder ID




					     Folder ID        File Statistics

						      Files




Label 3 DFD for process 7.4





      Folder Name					         
                                                                                                                                      Folders

											  Folder Statistics
					



									    Folder Statistics








Label 3 DFD for process 7.5


				  File Path
Folder ID			 				File


           
											File Name/
											File Statistics






                File having random file name
								           File		 File Statistics


									     File Statistics
 File Directory in the server


								           Files 



Label 3 DFD for process 7.3	



						                                                             File ID


	             Members					  Files		

          User Name         Member ID
				            Member ID

									  File IDs

User Name		          Member ID



								           Folder IDs
						        Member ID
										                File,Folder ID

								
				 	        Folders		
								   Folder ID


























6.2.2	ENTITY-RELATIONSHIP DIAGRAM

The data flow diagram does not reveal the relationships between the various data elements involved in the system. This relationship is the most important feature in a database system. This relationship is stated using an E-R Diagram.

         The most important consideration in designing the database  is how the information will be used. The various application and procedures that will use the database introduce the requirements upon the structure of the data. In a relational database, representation of data and data relationship is a collection of tables. Each tables has one or more columns.

The first step in creating a database is designing it. The tables that will be required and the data that each table will contain  are determined. How one table relates to another is also detemined. This is a important step and deserves careful consideration. The stored data elements are refered to as entities and how these elements are related is known as a relationship.

The E-R Diagram of the “ONLINE COLLABORATION SYSTEM” is as follows: -

Only some of the attributes of the entities have been shown in the diagram. The other attributes are given in the next page.



























6.2.2 ENTITY-RELATIONSHIP DIAGRAM












				Team

				Teamleader




































The other attributes of the entities described in E-R Diagram are given below: -


Members:                                          Messages:                                             Teams:

i.	PkMemberID                             i.    PkMessageID                                 i.  PkTeamID
ii.	FirstName                                  ii.   FkMessageToMemberID            ii. FkLeaderID
iii.	LastName                                  iii.   FkMessageFromMemberID      iv. Name
iv.	Email                                          iv.   MessageDate                                 v. Description
v.	UserName	          v.    MessageSubject
vi.	 Password	         vi.    MessageText
vii.	 DisplayProfile	        vii.    MessageRead
     viii.  Homephone
 ix.  Workphone
ix.	 Mobilephone
x.	 Fax
xi.	 AboutMe






TeamMembers:		              Files:					    Folders:

    i.  FkTeamID	                                 i.   PkFileID		                       i.  PkFolderID
   ii.  FkMemberID	                                ii.   FkTeamId			          ii.  FkTeamId
				         	      iii.   FkMemberID		         iii.  Name
                                              iv.   Name			         iv.  Description
                  			                    v.   Description			          v.  UploadDate
				                   vi.   FileSize			         vi.  FkCreater
				                  vii.   StoredAS
				                 viii.   uploadDate		
				                   ix.   FkCreater











6.2.3	Database Design:  -

                This is the most crucial part of the system design. The complete database description must confirm to the rules of logical and physical data structure imposed by the database management system that will manage the system. Designer for database design must understand the following aspects.


	The logical and physical data structure.
	The criterion that guides the transformation of a conceptual data model into the logical and physical data structure.
	Method of designing those databases using the structures and guidelines.


Table description of  “Online Collaboration System” Database


For my part of the project I have designed 6 tables: -

	Members            : Each user of the system has a member record in this table.

	Massages            : Massages sent to other members are stored in this table.

	Teams                : Members can create and be added to an unlimited numbers of teams. This table will store the team description and name.

	TeamMembers   : This join table links the Members table and Team  table to support a many-to-many relationship between the two tables.

	Files                     : Contains all the attributes of the file uploaded.

	Folders                : Contains all the attributes of the created folder.




Members: This Table is the largest of the four tables. It contains all the required and optional profile information for each member.

                       The required fields are integral to making the system work. The email address is required so that the user login id, team id etc can be sent to the user. Moreover the user can send emails also. The username will be verified to make sure that the user has only one account and no duplicate names are allowed. A stored procedures has been used for the same.



Field Name	Sql Data Type	Length	Other
PkMemberID	Int	4	Identity,primary key
FirstName	Varchar	40	Not Null
LastName	Varchar	40	Not Null
Email	Varchar	100	Not Null
UserName	Varchar	20	Not Null
Password	Varchar	20	Not Null
DisplayProfile	Char	1	Not Null,default ‘p’
Homephone	Varchar	40	
Workphone	Varchar	40	
Mobilephone	Varchar	40	
Fax	Varchar	40	
AboutMe	Text	120	



Message: It stores internal emails sent between users. Two foreign keys point to Members table so that the message can be linked to its sender and recipient. Each message has also messageread field indicating whether the user has actually open and read the message. 




Field Name	Sql Data Type	Length	Other
PkMessageID	Int	4	Identity,Primary Key
FkMessageToMemberID	Int	4	Not Null
FkMessageFromMemberID	Int	4	Not Null
MessageDate	Datetime	8	Not Null
MessageSubject	Varchar	80	Not Null
MessageText	Text	16	
MessageRead	Bit	1	









Teams: This Table keeps the records of the team that have been created in the system. Teams are the basis for the other application in the system. Files , messages etc can be made available publicly to everyone or just to particular member. The FkLeaderID foreign key points to the Members table. This identifies the leader of the team so that the user can maintain the team. 


Field Name	Sql Data Type	Length	Other
PkTeamID	Int	4	Identity,primary Key
FkLeaderID	Int	4	Not Null
Name	Varchar	80	Not Null
Description	Text	16	




TeamMembers :This table joins the Teams table with the Members in one to many relation that allows each team to have many members.





Field Name	Sql Data Type	Length	Other
FkTeamID	Int	N/A	Not Null
FkMemberID	Int	N/A	Not Null



Files  : This table keeps all the information regarding the files. It contains all the attributes of the file uploaded. Any file that are in the public file directory have a team id of zero.


       The file size is in bytes and is formatted for display into the logical unit(gigabyte,megabyte,kilobyte,byte). For security purposes, the real file name is hidden and a random one is generated which will be kept in the stored as field.










FIELD NAME	SQL DATA TYPE	LENGTH	OTHER
PkFileID	Int	4	Identity,Primary key
FkTeamId	Int	4	Notnull
FkMemberID	int	120	Notnull
Name	Varchar	50	
Description	Text	16	Notnull
FileSize	Bigint	120	Notnull
StoredAS	Varchar	120	Notnull
uploadDate	DateTime	8	Notnull
FkCreater	int	4	Notnull



Folders: This table keeps all the information regarding the folders. It contains a folder ID as primary key and if any file has been created within that folder then that folder ID has been kept as a reference in the file table corresponding to the file. Any folder that are in the public folder directory have a team id of zero.



FIELD NAME	SQL DATA TYPE	LENGTH	OTHER
PkFolderID	Int	4	Identity,Primary key
FkTeamId	Int	4	Notnull
Name	Varchar	50	Notnull
Description	Text	16	
UploadDate	Datetime	8	Notnull
FkCreater	Int	4	notnull














6.3	CODE SAMPLES

6.3.1 Data driven architecture used in the coding

The data driven architecture I have used for developing this application is the 3-tier. Since, simply getting hold of a database and knowing the commands for retrieving and maintaining the data it contains does not guarantee the creation of an application that can achieve the goals of modern software development. Some of its goals are: -

	Maintainability
	Performance
	Scalability
	Reusability

The 3-tier model, which consist of the following: -

1.Data tier: -
                                   Contains the database and stored procedures, and data access code.

2.Business tier: -
                                   The business tier of the application is where the majority of the application-specific functionality resides. Usually, this functionality consist of calling multiple atomic actions such as read, write, delete etc commands in order to insulate the presentation tier from the complexities of the rules that the application must conform to.

3.Presentation tier: - 
                                    Provides the user interface and control of process flow to the application, along with validation of user input. The presentation tier of the system is the only portion of the system that the end user gets to see, whether it’s collection of web pages or even a command prompt.

                                           

									       Data Tier





									        Business Tier


							     

									           Presentation Tier



6.3.2	CODE SAMPLES

  
6.3.2.1	STORED PROCEDURES USED FOR DEVELOPING PROPOSED SYSTEM

The stored procedures has been extensively used in the proposed system .The stored procedure improves modularization, security, reduced network traffic, increase speed etc. We can also do the process control through the stored procedure.

       Some of the stored procedures used in the system are: -

                  1.CheckForDuplicate :        CREATE  PROCEDURE  sp_CheckForduplicateEmail
                                                                @Email varchar (100)
                                                                AS
                                                                SELECT  COUNT(*) As DuplicateCount  FROM  Tab_Members
                                                                WHERE Lower(Email)=Lower(@Email)

                  2.CheckForDuplicateUsername :
 
                                                               CREATE  PROCEDURE  sp_CheckForduplicateUsername
                                                               @Username VarChar(20)
                                                               AS
                                                               SELECT  COUNT(*) As DuplicateCount FROM Tab_Members
                                                               WHERE Lower(UserName)=Lower(@Username)

                   3.CheckLogin              :
                      
                                                              CREATE  PROCEDURE  sp_CheckLogin
                                                             @Username VarChar(20)
				                   @Password VarChar(20)
                                                             AS
				                   SELECT  *  FROM Tab_Members 
                                                             WHERE  Lower(UserName)=Lower(@Username) AND
                                                             Lower(Password)=Lower(@Password)

                     4.CheckMessageCountByMember :

                                                           CREATE  PROCEDURE  sp_ CheckMessageCountByMember
                                                           @MemberID int,
				                 @Message_Visibility  VarChar(15)
                                                          AS
				                SELECT  UnreadMessageCount =
                                                         (SELECT  COUNT(*) FROM Tab_Message
WHERE FkMessageToMemberID=@MemberID  AND                     Message_Visibility=@Message_Visibility AND Message_Read=0),

                                                         ReadMessageCount =
                                                              (SELECT  COUNT(*) FROM Tab_Message
      WHERE FkMessageToMemberID=@MemberID  AND                              Message_Visibility=@Message_Visibility AND Message_Read=0)

5.RetrieveMessageByMember

                                               CREATE  PROCEDURE  sp_ RetrieveMessageByMember        
                                                     @MemberID int,
				           @Message_Visibility  VarChar(15)
		                                   AS
                                                     SELECT  *  FROM Tab_Message
                                                     WHERE FkMessageToMemberID=@MemberID 
                                                     AND  Message_Visibility=@Message_Visibility
                                                     ORDER BY MessageDate DESC

          6.RetrieveTeamMember

                              CREATE  PROCEDURE  sp_ RetrieveTeamMember
                              @TeamID int
                              AS
                              SELECT  FkMemberID  FROM  TabTeamMember  TM, TabTeamLeader TL
                              WHERE  TL.PkTeamID=@TeamId and TM.fkTeamID=@TeamID

           7.RetrieveTeamMember

                              CREATE  PROCEDURE  sp_ RetrieveTeamByMember
                              @MemberID int
                              AS
                               Select * from Teams  
                               Where fkLeaderID=@MemebrID

    8.RetrieveTeamMember

                              CREATE  PROCEDURE  sp_ RetrieveTotalFilesByTeam
                              @TeamID int
                              AS
SELECT COUNT(*) AS TotalFileCount,
MAX(UploadDate) As LastUploadDate
FROM Files
WHERE fkTeamID = @TeamID

7.RetrieveFolderByTeam :

                                          CREATE  PROCEDURE  sp_ RetrieveFolderByTeam
                                          @TeamID
                                          AS
                                          SELECT * FROM  Tab_Folders
                                          WHERE FkTeamId=@TeamID
                                          ORDER BY Name

8.RetrieveFilesByTeam :

                                          CREATE  PROCEDURE  sp_ RetrieveFilesByTeam
                                          @TeamID
                                          AS
                                          SELECT * FROM  Files
                                          WHERE FkTeamId=@TeamID
                                          ORDER BY Name

9.RetrieveFilesByFolder :

                                          CREATE  PROCEDURE  sp_ RetrieveFilesByFolder
                                          @FolderID
                                          AS
SELECT * FROM  Files
WHERE fkFolderID = @FolderID
ORDER BY Name

10.RetrieveFilesByTeamByFolder :

                                          CREATE  PROCEDURE  sp_ RetrieveFilesByTeamByFolder
                                          @FolderID int,
@TeamID
                                          AS
SELECT * FROM  Files
WHERE fkFolderID = @FolderID
AND fkTeamID = @TeamID
ORDER BY Name




                           







As mentioned earlier the data driven architecture used in the proposed system is 3-tier. The 3-tier architecture simply makes the code organization easy. It makes the code more manageable. The component can be shared with any ASP.NET application, hence code can be reuse. There are many more advantages of component based programming like performance improve etc.

A small portion of database component used in the application has been shown below. This component is used to execute a stored procedure in the database, which will return data according to the parameter passed.

A DATABASE COMPONENT

using System;
using System.Configuration;
using System.Data;
using System.Data.SqlClient;

namespace DataComponent
{
     public class DBUtil2
  {
          
        private string ConnectionString;
        public DBUtil2()
        {
 ConnectionString="Data             Source=localhost;database=onlineteamwork;uid=sa;password=surajrai;";
         }
   
        public SqlDataReader GetdataReader(string str,int teamid)
       {
                 SqlConnection sqlconn=new SqlConnection(ConnectionString);
                 SqlCommand objcommand=new SqlCommand(str,sqlconn);
                 objcommand.CommandText=str;
	     objcommand.CommandType=CommandType.StoredProcedure;

	     SqlParameter objparameter=new  SqlParameter("@teamid",SqlDbType.VarChar,15);
        
	     objcommand.Parameters.Add(objparameter);
        
	     objparameter.Direction=ParameterDirection.Input;
        
	     objparameter.Value=teamid;
       
	     SqlDataReader dr;

	     sqlconn.Open();

	     dr=objcommand.ExecuteReader();
                dr.Read();
                return dr;
         }

         Public DataSet  GetfromDatabase(string str,int id)
         {

                string query=str;
                DataSet ds = FillDataSet(query);
                Return ds;
          }

         private DataSet FillDataSet(string query)
         {
                SqlConnection sqlconn=new SqlConnection(ConnectionString);
                SqlCommand mycommand=new SqlCommand(query,sqlconn);
                SqlDataAdapter   da  =  new SqlDataAdapter(mycommand);

                DataSet  ds = new DataSet();

                Try
                {
                            sqlconn.Open();
		    da.Fill(ds);
                 }
                 finally
                 {
                            sqlconn.Close();
                 }    

                 return ds;
         }

         Public Function GetRow()
        {
               return ds.Tables[0].NewRow()
           }
}








ViewFilesFolders.CS Page

This page is used to display the public files and folders, team files and folders and files inside the folders. For doing this the above database component has been extensively used. This is the C-Sharp page and its .ASPX page has not been shown here.

using System;
using System.Text;
using System.Data;
using System.Data.SqlClient;
using System.Web.UI;
using System.Web.UI.WebControls;
using System.Web.UI.HtmlControls;
using System.Text;

public class viewfileclass :Page
{
    protected Label lblforall;  protected Label pageheader;  protected Label straction;
    private void Page_Load(object sender,EventArgs e)
   {
        string teamid=Request.QueryString["teamid"].ToString();
        int tid=Int32.Parse(teamid);

        string queryfolderid=Request.QueryString["folderid"].ToString();
        int folderid=Int32.Parse(queryfolderid);
           
        StringBuilder sb=new StringBuilder();     StringBuilder sb2=new StringBuilder();
        SqlDataReader dr;   SqlDataReader dr2;
        
        DataComponent.DBUtil2 DB=new DataComponent.DBUtil2();
       
         if ((Convert.ToString(Session["mid"]).Length)==0)        //getting the value of session varriable
                 Response.Redirect ("login.aspx");
       else{      
             try
            {
                 if (tid==0 && folderid==0)                 //if user has clicked public file library
                {
                 pageheader.Text="Public File Library";          
       sb2.AppendFormat("<td align=left><a href=uploadfile.aspx?tid={0}><b>Add a                             File</b></a></td>",tid); 
               sb2.Append("<td>&nbsp;|&nbsp;</td>");
               sb2.AppendFormat("<td><a href=folderCreate.aspx?tid={0}><b>Create    Folder</b></a></td>",tid);
               sb2.Append("<br>");
             }
          }   catch (Exception err)
              {
                      pageheader.Text="Error reading the database";
                      pageheader.Text+=err.Message;
               } 
          if (folderid > 0)      //if user has clicked a folder
       {
          try
          {
              dr=DB.GetdataReader("RetrieveFolderByTeam",folderid);
pageheader.Text=dr["name"]+"&nbsp;&nbspFolder";                   sb2.AppendFormat("<td><a href=uploadfile.aspx?fid={0}>Add a File</td>",dr["pkfolderid"]);
              dr.Close();
          }
          catch (Exception err)
          {
              pageheader.Text="Error reading the database";
              pageheader.Text+=err.Message;
          } 
            
       }

           if (tid > 0)       // if user’s team name has been clicked
           {
             try
             {
                dr=DB.GetdataReader("RetrieveFolderByTeam",tid);
                 pageheader.Text=dr["name"] +"&nbsp;&nbsp File Library";
                 sb2.AppendFormat("<td align=left><a href=uploadfile.aspx?tid={0}><b>Add a                   File</b></a></td>",tid);
                  sb2.Append("<td>&nbsp;|&nbsp;</td>");
                  sb2.AppendFormat("<td><a href=folderCreate.aspx?tid={0}><b>Create Folder</b></a></td>",tid);
                  sb2.Append("<br>");
                  dr.Close();
              }
              catch (Exception err)
            {
               pageheader.Text="Error reading the database";
               pageheader.Text+=err.Message;
            } 
}

            straction.Text=sb2.ToString();
                  
           
           try
           {
           dr=DB.GetdataReader("RetrieveFolderByTeam",tid);

         
                 while (dr.Read())
                 {
                  sb.Append("<tr class=rowheading>");
                  sb.AppendFormat("<td width=4% align=center><img src=image/folder/folder.gif></td>");
                  sb.AppendFormat("<td width=20% align=left><a  
href=viewfile.aspx?folderid={0}&teamid=0>{1}</td>",dr["pkfolderid"],dr["name"]);
                  sb.AppendFormat("<td width=25% align=center>{0}</td>",dr["description"]);
                  sb.AppendFormat("<td width=20% align=center>{0}</td>",dr["creationdate"]);
                  sb.AppendFormat("<td width=10% align=center></td>");
                  sb.AppendFormat("<td width=26% align=center><a  
href=filedownload.aspx?fileid={0}>Update|Delete</a>",dr["pkfolderid"]);
                  sb.Append("</tr>");
                 }
          dr.Close();
           
         if (tid > 0 && folderid == 0)
         {

              dr2=DB.GetdataReader("RetrieveFilesByTeam",tid);

              while (dr2.Read())
              {
                  sb.Append("<tr class=rowheading>");
                  sb.AppendFormat("<td width=4% align=center><img src=image/folder/file.gif></td>");
                  sb.AppendFormat("<td width=20% align=left>{0}</td>",dr2["filename"]);
                  sb.AppendFormat("<td width=25% align=center>{0}</td>",dr2["description"]);
                  sb.AppendFormat("<td width=20% align=center>{0}</td>",dr2["uploaddate"]);
                  sb.AppendFormat("<td width=10% align=center>{0} byte</td>",dr2["filesize"]);
                  sb.AppendFormat("<td width=20% align=center><a                    
href=filedownload.aspx?fileid={0}>Download</a>",dr2["pkfileid"]);
                  sb.Append("</tr>");
          
}
              dr2.Close();
         }

       }
       catch (Exception err)
       {
              pageheader.Text="Error reading the database";
              pageheader.Text+=err.Message;
       } 

       if (folderid > 0 && tid == 0)
       {

              dr2=DB.GetdataReader("RetrievefilesByFolder",folderid);

              while (dr2.Read())
              {
                  sb.Append("<tr class=rowheading>");
                  sb.AppendFormat("<td width=4% align=center><img src=image/folder/file.gif></td>");
                  sb.AppendFormat("<td width=20% align=left>{0}</td>",dr2["filename"]);
                  sb.AppendFormat("<td width=25% align=center>{0}</td>",dr2["description"]);
                  sb.AppendFormat("<td width=20% align=center>{0}</td>",dr2["uploaddate"]);
                  sb.AppendFormat("<td width=10% align=center>{0} byte</td>",dr2["filesize"]);
                  sb.AppendFormat("<td width=20% align=center><a                    
href=filedownload.aspx?fileid={0}>Download</a>",dr2["pkfileid"]);
                  sb.Append("</tr>");
              }
       }
           
       lblforall.Text=sb.ToString();

     }
   }
}

