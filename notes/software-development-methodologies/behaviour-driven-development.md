---
title: Behaviour Driven Development
description: Explains about Behaviour Driven Development in brief.
---

BDD is software development process that emerges from test driven development.  
BDD combines the general technique of principles of TDD with ideas from Domain Driven Design and Analysis and design to provide software development and management, teams with shared tools and a shared process to collaborate on software development.


BDD is largely faciliated throught the use of a simple domain specific language using natural language constructs that can express the behaviour and the expected outcomes.  
BDD is considered an effective technical practice especially then the problem space of the business problem to solve is complex.


## Principles of BDD
1. BDD specifies that tests of any unit of software should be specified in terms of the desired behavior of the unit.
2. BDD, also related to how the desired behaviour should be specified.
3. BDD specified business analysis and developer should collaborate and should specify behaviour in terms of user stories.


> Scenario/Story:   
Returns got stock.

> As a:  
Store Owner

> In order to keep track of stock,  
> I want to add items back to stock when they're returned.

---

> Scenario/Story:
Refunded item should be returned to stock.

> Given that a customer previously brought a black sweaters from the store.    
> And I have there 3 black sweaters in stock.  
> When they return the black sweater for a refund, Then, there should have 4 black sweaters in stock.  
