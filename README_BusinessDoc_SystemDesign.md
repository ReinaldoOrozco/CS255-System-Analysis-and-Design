1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
   - The DriverPass project focused on designing a complete training and testing support system for driving schools' business. The client, DriverPass needed a system that procides students with online practice exams, scheduling for the on the road training and access to learning materials. Their main problem was that 65% of students fail their driving tests because they only study previous test questions.
   - To solve this, I designed a web-based platform that supports:
     . Practice exams
     . Lessons Scheduling
     . Instructor availability management
     . Secure payments
     . Administrative tools for IT and management
     
   - All these functions are reflected in the technical requirements of the system design document, which states that the system must support scheduling lessons, managing user accounts, processing     payments, delivering DMV updates and providing online practice tests.

2. What did you do particularly well?'
- I excelled at interpreting the client's needs and translating them into clear, structured requirements. For example, the business Requirements Documents a complete set of functional requirements such as:
    . The system allows students to take online practice exams and
    . The system allows students to schedule on-the-road lessons.
- I also did well in defining nonfunctional requirements like performance, security adaptability and platform constraints. These were detailed and aligned with real world system expectations, such as requiring HTTPS, password encryption and cloud hosting.
  
3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
- If i were to revise one part of my work, I would improve the UML diagrams section of the System Design Document. The template sections for the use case diagram, activity diagrams, sequence diagram and class diagram were present but not populated.

- Adding complete UML diagrams would strengthen the design phase by visually showing:
  . Actor interactions
  . System workflows
  . Object relationships
  . Message flows

- This would make the System Design Document more complete and more aligned with industry expectations. 

4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
   - I interpreted user needs by closely analyzing the interview transcript and translating each stakeholder concerns into system requirements. For example, the Business Requirements Documents states:
     . Role-based access control
     . Database tables for each user type
     . RESTful API endpoints for scheduling, tests, payments, and user management
     
   - Considering user needs is essential because systems fail when they don't match real workflows. A system must reflect how people actually work, not how developers assume they work. This ensures usability, adoptions and long-term success.
     
5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
   - My approach to software design is structured and iterative:

a. Requirement Gathering:
I start by understanding the clients' goals, pain points and constraints. In this project, I used the interview transcript and converted each need into functional and nonfunctional requirements.

b. Modeling System:
I use diagrams (use case, activity, sequence, class) to visualize how the system behaves. Even though the diagrams were not fully completed in this project, the technical requirements were clearly derived from them.

c. Technical Planning:
I define the hardware, software, database, and security requirements. For example, the System Design Documents specifies:
- Relational database management system (MySQL, PostgreSQL or SQL Server)
- Authentication and authorization framework (JWT or OAuth2)

d. Iterative Refinement
I revisit requirements and adjust the design as new information emerges.

Strategies for the future:
- Creating complete UML diagrams early to clarify system behavior
- Using user stories to capture real-world workflows
- Applying modular design to support scalability
- Validating requirements with stakeholders before development begin



       
