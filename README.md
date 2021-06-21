# CS-255


Business Requirements Document  

CS 255 Business Requirements Document Template

Complete this template by replacing the bracketed text with the relevant information.

This template lays out all the different sections that you need to complete for Project One. Each section has guiding questions to prompt your thinking. These questions are meant to guide your initial responses to each area. You are encouraged to go beyond these questions using what you have learned in your readings. You will need to continually reference the interview transcript as you work to make sure that you are addressing your client’s needs. There is no required length for the final document. Instead, the goal is to complete each section based on your client’s needs.

Tip: You should respond in a bulleted list for each section. This will make your thoughts easier to reference when you move into the design phase for Project Two. One starter bullet has been provided for you in each section, but you will need to add more.
System Components and Design
Purpose
What is the purpose of this project? Who is the client and what do they want their system to be able to do?
•	The purpose of DriverPass is to build a platform that allows customers with the proper training to pass their written and on the road exams. DriverPass wants to build a system that will allow their customers to book and modify reservations for driving lessons, as well as provide different driving packages based on the customer’s needs. 


System Background
What does DriverPass want the system to do? What is the problem they want to fix? What are the different components needed for this system?

•	DriverPass wants their system to be able to access data from anywhere, online & offline, this will allow the owner to download reports from any location. The problem they are looking to fix is building a system that allows better driver training. They noticed that a lot of people fail their driving test, so starting this company will allow them to stay within the DMV requirements while allowing customers the proper training to pass the written and on the road exam. Some components that will be needed for this system are making sure the system runs off web and over the cloud. 

Objectives and Goals
What should this system be able to do when it is completed? What measurable tasks need to be included in the system design to achieve this?
•	When completed the system should be able to 
o	run off web and the cloud, 
o	have a data base that holds all customer information. 
o	A space that allows customers to book and modify reservations for multiple types of training.
o	Give the customers access to online test.
o	 Allow them to see what’s been completed and what’s next.  
o	We can measure these tasks by setting dates for creating our case diagrams and getting customer approval before we start building the user interface. 

Requirements
Nonfunctional Requirements
In this section, you will detail the different nonfunctional requirements for the DriverPass system. You will need to think about the different things that the system needs to function properly.

Performance Requirements
What environments (web-based, application, etc.) does this system need to run in? How fast should the system run? How often should the system be updated?
•	The system we build should be web based.
•	Quick load time for users 
•	The system should have quick load times between two and five seconds. 
•	The system should be updated frequently with little to no downtime in between updates.


Platform Constraints
What platforms (Windows, Unix, etc.) should the system run on? Does the back end require any tools, such as a database, to support this application?
•	The system should primarily run on all desktops such as Safari, Chrome, & IE 
•	 Responsive for all mobile devices
•	The backend should have a database that can manage and store all user information. 

Accuracy and Precision
How will you distinguish between different users? Is the input case-sensitive? When should the system inform the admin of a problem?
•	We can distinguish different users by taking advantage of Google analytics cookies usage in between different sessions. 
•	The system will provide notifications and daily reports to the admin.
•	All passwords required by users will be case sensitive, making users have a combination of letters, numbers, and punctuation marks. 

Adaptability 
Can you make changes to the user (add/remove/modify) without changing code? How will the system adapt to platform updates? What type of access does the IT admin need? 
•	If the website stays up to date, changes can be made without breaking code. 
•	IT will have admin access so that they can make changes to users’ profile without breaking code. 
•	To avoid breaking code all user changes should be done on the backend. 


Security
What is required for the user to log in? How can you secure the connection or the data exchange between the client and the server? What should happen to the account if there is a “brute force” hacking attempt? What happens if the user forgets their password? 
•	Email address and passwords are required for login.
•	SSL can be used to secure the connection of the data exchange between the client and server. 
•	The account will be locked after 3 failed password attempts. 
•	If the user has forgotten their password, they will be able to reset it using the email address on file. 

Functional Requirements
Using the information from the scenario, think about the different functions the system needs to provide. Each of your bullets should start with “The system shall . . .” For example, one functional requirement might be, “The system shall validate user credentials when logging in.”
•	The system shall send emails with a link to reset your password. 
•	The system shall lock user accounts after 3 failed attempts. 
•	The system shall notify the company when the DMV laws have changed. 
•	The system shall send appointment confirmation emails. 
•	The system shall appointment reminder emails a day before the schedule appointment. 

User Interface
What are the needs of the interface? Who are the different users for this interface? What will each user need to be able to do through the interface? How will the user interact with the interface (mobile, browser, etc.)? 
•	The interface should be web based but also responsive for mobile and desktop users. 
•	The users for this interface will be people looking to learn how to drive and or book drivers test appointments. 
•	Each user should be able to login, book and modify appointments, update their information, and have access to all packages that are available for them to book. 
•	The user can interact with our interface via mobile device or any web supported browser. 

Assumptions
What things were not specifically addressed in your design above? What assumptions are you making in your design about the users or the technology they have? 
•	I’m assuming that most customers will have access to 
o	Mobile devices 
o	Desktop devices 
o	Email address 


Limitations
Any system you build will naturally have limitations. What limitations do you see in your system design? What limitations do you have as far as resources, time, budget, or technology?
•	Not enough time to complete the project. 
•	Not getting updated enough on the changes that the DMV have made. 

Gantt Chart
Please include a screenshot of the GANTT chart that you created with Lucidchart. Be sure to check that it meets the plan described by the characters in the interview.
![Gantt chart with timeline](https://user-images.githubusercontent.com/69543005/122817084-5b109580-d28c-11eb-9b42-d64d3f78bd69.jpeg)


System Design Doucment 

CS 255 System Design Document Template

This template lays out all the different sections that you need to complete for Project Two. Each section has guidance to prompt your thinking. You will need to continually reference the interview transcript as you work to make sure that you are addressing your client’s needs. There is no required length for the final document. Instead the goal is to complete each section based on what your client’s needs are. Remove this note when you are finished, and replace all bracketed text with the relevant information.

UML Diagrams

UML Use Case Diagram

![image](https://user-images.githubusercontent.com/69543005/122817300-9612c900-d28c-11eb-9e24-01550ca63377.png)


UML Activity Diagrams

![image](https://user-images.githubusercontent.com/69543005/122817321-9dd26d80-d28c-11eb-97ca-9a4eaa599cd8.png)

![image](https://user-images.githubusercontent.com/69543005/122817332-a0cd5e00-d28c-11eb-80c0-e89f94fcd4bd.png)

UML Sequence Diagram
[You were asked to create a sequence diagram based on one of the use cases you chose. Please insert your sequence diagram here. Check to make sure that you included appropriate components and symbols and that your design meets the client’s needs.]

![image](https://user-images.githubusercontent.com/69543005/122817359-aa56c600-d28c-11eb-8717-5478693a1675.png)


UML Class Diagram 

![image](https://user-images.githubusercontent.com/69543005/122817387-b2166a80-d28c-11eb-837a-b15002a98e5f.png)


Technical Requirements

•	The system should primarily run on all desktops such as Safari, Chrome, & IE.
•	Responsive for all mobile devices.
•	The backend should have a database that can manage and store all user information. 
•	The system we build should be web based.
•	The system should have quick load times between two and five seconds. 
•	The system should be updated frequently with little to no downtime in between updates.
•	The system should be able to process payments.
•	The system should be able to track and modify appointments. 









