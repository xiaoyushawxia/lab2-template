# OOSD LAB 2: Weeks 6-11

This assessment is _individual_. You are not allowed to publish your assignment, copy the repository, share the solution with teammates, or anything of the like. Refer to the standard warning in Canvas.



## Introduction
This assessment evaluates the following CLOs

- CLO2: Identify and mitigate the risks associated with the development of large-scale software projects.
- CLO3: Apply the UML design notation as part of the OO development process.
- CLO4: Explain and document diagrammatically specific Design Patterns from established pattern catalogues and apply them to novel design problems.


The following topics are assessed:

- Week 6: Creational Patterns.
- Week 7-8: Structural Patterns.
- Week 9-10: Behavioural Patterns.
- Week 11: Architectural Patterns




## Assignment Activities [MANDATORY]


### Task 1: src/main/java/task1 (20 marks)

**SCENARIO:** 

>The company is in need of developing an application to manage their employee’s data and print their payslips. Assuming that their employees are of 5 types: 
>
> - Salaried employees who are paid a fixed monthly salary regardless of the number of hours worked and paid leave hours.
> - Contract employees who are paid a fixed monthly salary regardless of the number of hours worked.
> - Casual employees who are paid by the hour and receive overtime pay (i.e., double hourly salary rate) for all hours worked inexcess of 38 hours.
> - Commission employees who are paid a base salary plus a commission of 25% of their sales. 
> - Commission interns who are paid a commission of 15% of their sales. 
>
> The company wants to write an application that performs its payroll calculations and has other database management functions like retrieval of records, adding and deleting of records, etc. The company wants you to write an application that performs the following functions.
> - The admin can log in and log out to the system.
> - After login, the system should provide options like adding new employee records, changing employee’s details, navigating through employee’s details and making a search for an employee’s details.
> - The system should also allow to printing of the employee’s payslips.


**ACTIVITIES**

1. Based on the requirements in the above case study, you need to design and build the class diagram with the attributes and operations of each class. You must include the relationships that are needed. Save it as a `png` file in the corresponding folder.

2. Use the `ANSWER.md` file to explain _which_ behavioural and architectural patterns you selected, and _which_. You need to justify your decision, so be as extensive as needed. You are _not_ allowed to copy-paste definitions, you need to explain everything in the context of the example. 
    * If you used creational patterns, you can simply name those without any further explanation needed (only in the case of creational patterns).

3. Implement the code for the diagram above. The code inside the methods can be a dummy return, or have a `//TODO` comment that explains the logic that should be implemented.


 
 
 <br /> <br />


#### Task 2: src/main/java/task2 [10 marks]

In this section “design pattern” refers to the catalogue of patterns by Gamma et al. that were presented in this course and the immutable data structure patterns.

For each of the three scenarios below state which design pattern can best solve the problem and explain (in the space provided) how the design pattern is applied to the specific case. Provide a class diagram for each scenario as well.

4. A GUI-driven application is planned with a standard model view controller (MVC) design which has many views, many controllers and a single model. The model functionality is complex and so is the GUI thus a single user action (such as a menu selection or a button press) will require the participation of many view and controller objects working together to be synchronised. Please use at least two views (i.e., CardView and LayoutView) and two controllers (i.e., CardController and LayoutController) in the diagram.	 


5. A cross-platform GUI toolkit has many widgets and components and is designed to run on multiple platforms such as Windows, Linux, macOS, Android and iOS. New platforms should also be supported with minimal changes to client code.    

6. A diagramming application provides multi-level undo based on a history of operations that have been performed on the diagram.




<br /><br />



#### Task 3: src/main/java/task3 [10 marks]

**SCENARIO**

> Melbourne Travel, which hires flights from different airlines, wants to offer customised on-board meals based on travel distance. There are two categories of flights: short trip and long distance. The short trip meal consists of a snack and a soft drink, while a full meal for a long-distance flight comprises an appetizer, main, salad, dessert and drink. While the customer can choose different items in each category (main, dessert, snack, etc.) they must choose from the specific items served by each of the hired airlines. For example, the dessert category for Virgin Airlines might include ice cream and jelly, whereas the main category for Singapore Airlines might include chicken, beef, fish and a vegetarian option.
>
> You are required to develop a design that simplifies the following extensions:
>
> (1) new types of meals (i.e., appetizer, main, dessert and drink for a medium-distance flight);
> (2) new airlines which provide different meal options in each category.


7. Draw a class diagram for your proposed solution incorporating at least two design patterns using the naming of the problem domain, i.e., do not just draw generic pattern diagrams that do not apply to the airline meal scenario. Your class diagram should include both of the concrete meal types described above (snack and full meal). For brevity, you can specify a single concrete airline and a single meal item for each category for that airline but should clearly indicate where additional concrete classes sit in the class hierarchy. Use the `Answers.md` file to add any additional explanation you may need.


8. Explain briefly how the design patterns facilitate extensibility based on points (1) and (2) above (one or two paragraphs each). Pay particular attention to how changes are isolated from client code.












## Rubric

Please, check the rubric detailed in Canvas.
