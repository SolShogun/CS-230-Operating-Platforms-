# CS 230 – Operating Platforms

**Student:** Shamika Jaudon  
**Course:** CS 230 – Operating Platforms  
**Project:** The Gaming Room – Draw It or Lose It  
**Artifact:** Software Design Document

## Project Overview

The Gaming Room is a client that wanted to expand its existing Android-based game, *Draw It or Lose It*, into a web-based application that could be accessed across multiple operating platforms and devices. The game is similar to a television drawing competition where players guess images as they are gradually revealed.

The client required a scalable, secure, and reliable application that could support multiple teams and players simultaneously. Each game session needed a unique identifier, and the system had to prevent duplicate game and team names. The application also needed centralized game management, efficient memory usage, and compatibility across Windows, macOS, Linux, and mobile devices.

## Reflection

### 1. What did you do particularly well in developing this documentation?

One area where I performed particularly well was analyzing the different operating platforms and recommending an appropriate architecture for The Gaming Room. I compared Windows, Linux, macOS, and mobile operating environments while considering performance, scalability, security, and cost.

I also effectively documented the advantages of using a client-server architecture with a Linux-based server. My recommendations focused on providing the client with a practical solution that supports future expansion while maintaining reliable application performance.

### 2. What about the process of working through a design document did you find helpful when developing the code?

Developing the software design document helped me understand the importance of planning an application's structure before beginning development. Identifying the requirements, system components, and relationships between classes provided a clear foundation for implementation.

The process also helped me understand how object-oriented programming principles, such as inheritance, encapsulation, and the singleton pattern, can be applied to real-world applications. Having a documented design made it easier to organize the code, reduce unnecessary duplication, and ensure that the application aligned with the client's expectations.

### 3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my software design document, I would expand the security and scalability recommendations. Although I addressed authentication, authorization, and operating system security, I would include more detailed information about protecting user sessions, securing communication between clients and servers, and managing increased application traffic.

I would also add architectural diagrams illustrating how the application components communicate. These improvements would make the document more useful for developers and provide the client with a clearer understanding of the proposed solution.

### 4. How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I interpreted the client's needs by carefully reviewing the project requirements and identifying the features necessary for the application's successful expansion. The Gaming Room needed a solution that could operate across different devices, support multiple users, maintain unique game sessions, and provide consistent performance.

I incorporated these requirements by recommending a web-based client-server architecture with centralized application management. This approach allows users to access the game through compatible web browsers while the server manages game sessions, authentication, and application logic.

Considering user needs is essential because software should solve the client's actual problems rather than simply demonstrate technical capabilities. Understanding user expectations helps developers create applications that are functional, accessible, reliable, and easier to maintain.

### 5. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach to software design began with identifying the client's requirements and evaluating the available technical solutions. I analyzed operating system architectures, memory and storage management, distributed systems, and security considerations before selecting an appropriate platform.

I also used object-oriented design principles and evaluated how the application's components would interact within a client-server environment.

For future projects, I would continue using a requirements-first approach while incorporating UML diagrams, architecture comparisons, security assessments, and prototype testing. I would also use iterative development practices to gather feedback throughout the design process and make improvements before final implementation.

## Conclusion

The CS 230 project strengthened my understanding of software architecture, operating platforms, and the importance of effective technical documentation. Working with The Gaming Room demonstrated how software design decisions influence performance, security, scalability, and user experience.

This project also helped me develop skills in evaluating technical alternatives and communicating recommendations to both technical and nontechnical stakeholders. These skills will be valuable as I continue developing software applications and pursuing opportunities in computer science.

## Portfolio Artifact

**Software Design Document:** Draw It or Lose It – CS 230 Project Three

The completed software design document is included in this repository and demonstrates my ability to analyze system requirements, compare operating platforms, and recommend a scalable software architecture.
