Hello, I am adding my submitted project one: business requirements document and the project two: system design document to my README information for the course CS255.

System Components and Design
Purpose
What is the purpose of this project? Who is the client and what do they want their system to be able to do?
The project aims to design and develop a system for DriverPass which is a driver training company that helps and aids student drivers in passing their driving test. This system will include online practice tests and on-the-road training, equipping students with the necessary skills to succeed in obtaining their driving licenses.

System Background
What does DriverPass want the system to do? What is the problem they want to fix? What are the different components needed for this system?
DriverPass intends on improving student success rates by offering a system that integrates online classes, practice tests, and hands-on training. The system will enable users to access their data both online and offline, providing functionalities for managing reservations, tracking activities, and ensuring compliance with the latest DMV rules, local laws, and policies. It will support multiple user roles with varying access levels and feature a user-friendly interface for seamless interaction.

Objectives and Goals
What should this system be able to do when it is completed? What measurable tasks need to be included in the system design to achieve this?
The system for DriverPass should be able to complete the following tasks, deliver online courses and practice exams for driving license preparation. Enable users to schedule, modify, or change their driving lessons appointments and schedule to better adapt to their needs. Remind users to stay up to date on local state laws, DMV or DPS rules and policies, while training or learning. Ensure data is secure while using the online learning platform. Create intuitive and visually aesthetic learning interfaces that are easy to use for students, parents, or instructors, etc. 

Requirements
Nonfunctional Requirements
In this section, you will detail the different nonfunctional requirements for the DriverPass system. You will need to think about the different things that the system needs to function properly.

Performance Requirements
What environments (web-based, application, etc.) does this system need to run in? How fast should the system run? How often should the system be updated?
I believe this and many other online learning platforms should be web based, similar to how schools, institutions, and job learning websites run. This will allow for the fastest method of running on a multitude of systems from windows, mac, linux, etc. The system should be able to handle multiple users, admins, and instructors to be able to access the site, its materials, and its data at any given moment. The system should also be able to work with different time zones for different users, as to not conflict with instructor schedules. 

Platform Constraints
What platforms (Windows, Unix, etc.) should the system run on? Does the back end require any tools, such as a database, to support this application?
The system needs to be able to run on web browsers so that it is more accessible and less resource heavy on the user side. DriverPass should be accessible via web browsers and mobile devices as well as compatible with popular operating systems, including Windows, macOS, linux, iOS, and Android devices.


Accuracy and Precision
How will you distinguish between different users? Is the input case-sensitive? When should the system inform the admin of a problem?
The DriverPass system needs to be able to differentiate between users such as different students, instructors, platform admins etc. The system should use unique identifiers such as emails, passwords, phone numbers, potentially even usernames. User input should always be case sensitive to validate that the user is inputting their information correctly and so that the system can confirm that the appropriate user is accessing the system. Live time security updates and scans is vital to keep any system up and running so that platform admins are aware of any security compromises, some examples of this would be a report of too many sign in attempts may indicate that someone is trying to break into an account.

Adaptability 
Can you make changes to the user (add/remove/modify) without changing code? How will the system adapt to platform updates? What type of access does the IT admin need? 
[Insert text]

Security
What is required for the user to log in? How can you secure the connection or the data exchange between the client and the server? What should happen to the account if there is a “brute force” hacking attempt? What happens if the user forgets their password? 
A user is required to input personal data such as their name, address, phone number, email, payment or bank info. To ensure that the information is secure and is safely connected for data exchanging would be practicing safe precautions such as choosing a secure password, utilizing MFA, changing password frequently, some websites even allow sign in for specific devices and limits the number of devices an account can be signed into. If a user forgets their password, the most standard procedure is sending a OTP code that can unlock or change the password usually into a device or account that the user already has access to, i.e. their email, their phone, or even a federation such as facebook, google, etc.
Functional Requirements
Using the information from the scenario, think about the different functions the system needs to provide. Each of your bullets should start with “The system shall . . .” For example, one functional requirement might be, “The system shall validate user credentials when logging in.”
the system should be able to meet the functional requirements such as 
Provide an user friendly interface for easy navigation, Show on screen live time user progress, including completed and ongoing tests, with details like test name, time taken, score, and status, Provide scheduling, modification, and cancellation of driving lessons online, Include functionality for users to contact DriverPass and receive prompt responses.


User Interface
What are the needs of the interface? Who are the different users for this interface? What will each user need to be able to do through the interface? How will the user interact with the interface (mobile, browser, etc.)? 
The system should show a user sign in option, upon logging in the user should be able to see their account, any upcoming tests, learning, classes, etc and their overall schedule, Grades that are changing real time to show the users current progress and how far along they are in their course(s)

Assumptions
What things were not specifically addressed in your design above? What assumptions are you making in your design about the users or the technology they have? 
some assumptions that are made will be that the user will have a reliable internet connection that can access the material without lag, the user will have computer literacy and or competency to complete their course material, the system will host the learning and store information. 

Limitations
Any system you build will naturally have limitations. What limitations do you see in your system design? What limitations do you have as far as resources, time, budget, or technology?
Limitations include, number of users that the system can support at one time, number of courses held can be due to budget perhaps DriverPass can only hire X amount of staff. Continuous monitoring and underlying security protocol to ensure the system is not being compromised, would require more resources and potentially that is not available. 


***********************************************************************************************************
UML Use Case Diagram
[In Module Six, you were asked to complete a use case diagram based on your system design. If you would like to make any adjustments to your diagram, please do so. Please insert your use case diagram here. Check to make sure that you included appropriate components and symbols and that your design meets the client’s needs.]

UML Activity Diagrams
[You were asked to choose two use cases and create two activity diagrams, one for each use case. Please insert both of your activity diagrams here. Check to make sure that you included appropriate components and symbols and that your design meets the client’s needs.]



UML Sequence Diagram
[You were asked to create a sequence diagram based on one of the use cases you chose. Please insert your sequence diagram here. Check to make sure that you included appropriate components and symbols and that your design meets the client’s needs.]


UML Class Diagram
[You were asked to create a class diagram based on the different classes and attributes needed for your system design. You are not required to include methods, but you may if you wish. Please insert your class diagram here. Check to make sure that you included appropriate components and symbols and that your design meets the client’s requirements.]
https://github.com/WitherSlayer597/Portfolio/blob/main/diagram.jpg

Technical Requirements
[Based on the diagrams you have created, describe the technical requirements of your system. These requirements should address the required hardware, software, tools, and infrastructure necessary for your system design.]



The system for DriverPass should be able to complete the following tasks, deliver online courses and practice exams for driving license preparation. Enable users to schedule, modify, or change their driving lessons appointments and schedule to better adapt to their needs. Remind users to stay up to date on local state laws, DMV or DPS rules and policies, while training or learning. Ensure data is secure while using the online learning platform. Create intuitive and visually aesthetic learning interfaces that are easy to use for students, parents, or instructors, etc. this and many other online learning platforms should be web based, similar to how schools, institutions, and job learning websites run. This will allow for the fastest method of running on a multitude of systems from windows, mac, linux, etc. The system should be able to handle multiple users, admins, and instructors to be able to access the site, its materials, and its data at any given moment. The system should also be able to work with different time zones for different users, as to not conflict with instructor schedules. The system needs to be able to run on web browsers so that it is more accessible and less resource heavy on the user side. DriverPass should be accessible via web browsers and mobile devices as well as compatible with popular operating systems, including Windows, macOS, linux, iOS, and Android devices.DriverPass system needs to be able to differentiate between users such as different students, instructors, platform admins etc. The system should use unique identifiers such as emails, passwords, phone numbers, potentially even usernames. User input should always be case sensitive to validate that the user is inputting their information correctly and so that the system can confirm that the appropriate user is accessing the system. Live time security updates and scans is vital to keep any system up and running so that platform admins are aware of any security compromises, some examples of this would be a report of too many sign in attempts may indicate that someone is trying to break into an account.
