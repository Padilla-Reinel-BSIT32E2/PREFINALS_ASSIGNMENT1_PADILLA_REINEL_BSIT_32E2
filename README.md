# PREFINALS_ASSIGNMENT1_PADILLA_REINEL_BSIT_32E2

Conceptual Understanding:

Onion Architecture:
Have you heard of the Onion Architecture principle in software design?
Answer: Yes

MVC Pattern:
Are you familiar with the Model-View-Controller (MVC) pattern for building web applications?
Answer: Yes

Web API:
Do you understand the concept of building RESTful APIs using ASP.NET Core Web API?
Answer: No

Application & Bottlenecks:

Onion Architecture:

Benefits:
Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)
Answer:
The code is organized into distinct layers, providing clarity on the role of each part of the application. This structure simplifies making changes, as it helps locate and modify the right part of the code without impacting the entire application.

Bottlenecks (Encountered):
Have you encountered any challenges with Onion Architecture in your projects? If so, briefly describe the bottleneck(s). (e.g., Increased complexity for simple projects, difficulty finding developers familiar with the pattern)
Answer:
Yes, I have faced challenges in understanding Onion Architecture. I frequently encounter errors and find it difficult to grasp how this architectural style works.

MVC:

Components:
Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
Answer:
Model - Manages data and business logic, handling data processing and rules.
View - Displays data to the user, representing the user interface.
Controller - Acts as a bridge between Model and View, handling user input and updating the Model.

Bottlenecks (Encountered):
Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit testing controllers, logic changes rippling through the application)
Answer:
Yes, sometimes it's complicated, but I understand the basics.

Web API:

Differences from MVC:
Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
Answer:
Traditional MVC applications are built to create full web applications using the Model-View-Controller pattern. They involve Models for managing data and business logic, Views for rendering HTML pages, and Controllers for handling user interactions. These applications primarily generate dynamic web pages for user interaction through a browser.

On the other hand, Web APIs focus on providing data services rather than full web applications. They use Models to manage data and Controllers to handle requests, but do not use Views. Instead of rendering HTML, Web APIs return data in formats like JSON or XML, designed to be consumed by other applications or services, allowing programmatic access to data and functionality without a user interface.

Bottlenecks (Encountered):
Have you encountered any performance challenges with traditional MVC applications compared to Web APIs? If so, briefly describe the scenario(s). (e.g., Frequent page refreshes causing performance overhead, complex data exchange requiring a more lightweight approach)
Answer:
Yes, understanding the differences between the two, traditional MVC applications tend to be more complex than Web APIs. For instance, there are often numerous changes required to run or fix errors in traditional MVC, making them more cumbersome compared to the relatively straightforward nature of Web APIs.
