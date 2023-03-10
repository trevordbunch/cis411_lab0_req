# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Luke Hardman  
**GitHub Handle:** LAHardman  
**Repository:** https://github.com/LAHardman/cis411_lab0_req
___

## 1. Overview
The development of a use case for a business system that can facilitate ordering a meal from an on-campus provider and having it delivered to the classroom of the person who placed the order.
![Use Case](https://github.com/LAHardman/cis411_lab0_req/blob/main/assets/useCase.png?raw=true)
## 2. Requirements

    Business: The business objective that the system needs to satisfy.
        B.1 The system must limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 minutes of promised delivery is not placed in jeopardy. (Pointy Hair Boss)
        B.2 The system must be able to lengthen promised delivery time or turn off orders dependent on weather conditions, so that the staff are not endangered from deliveries. (Flat Hair Boss)
        B.3 The system must allow for tracking of all orders to ensure timely delivery and to monitor the performance of delivery staff. (Pointy Hair Boss)
        B.4 The system must allow for easy integration with other existing systems and tools used by the business, such as financial systems, customer relationship management systems, and marketing automation tools. 
    User: The actions that a user takes within the system
        U.1 The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Hungry Student 1).
        U.2 The user should be able to choose which food provider they want to get each item from (Tim).
        U.3 The user must be able to view their order history and track the status of current orders. (Hungry Student 1)
        U.4 The user should be able to modify or cancel their order up until a certain point in the order process. (Tim)
    Functional: The functions should the system perform
        F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Hangry Student 2).
        F.2 The system must display an order confirmation once the order has been properly gone through (Papa John Pizza).
        F.3 The system must send notifications to the user when their order is confirmed, when it is being prepared, and when it has been delivered. (Hangry Student 2)
        F.4 The system must provide a rating and feedback system for users to rate their experience with the food providers and delivery staff. (Papa John Pizza)
    Non-Functional: The characteristics that the system should have.
        N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
        N.2 The system must be accessible on all devices, including desktop, laptop, tablet, and mobile devices. (UX Expert Lady)
        N.3 The system must be able to handle high volumes of orders during peak times without slowing down or crashing. (UX Expert Lady)
    System: Specifications about how the system should be built.
        S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
        S.2 The system must comply with all relevant data privacy and security regulations.
        S.3 The system must have a robust backup and disaster recovery plan in place to ensure that data and information are protected in case of a system failure or data loss.


## 3. Assumptions
We are assuming the following in regards to the system:
1. The school is capable of holding students accountable for the amount of money they spend on their orders
2. Orders will only be placed to classrooms
3. Students will be accountable for picking up their orders from the designated location

## Appendix: GitHub Notes

### A.1 Forked Repository
![Fork Relational Diagram](https://github.com/LAHardman/cis411_lab0_req/blob/main/assets/forkDiagram.png?raw=true)
### A.2 Git Logs
```c6a26dd (HEAD -> main, labreport) updated requirements
0d63669 (origin/labreport) My commit for fork of @trevorbunch lab
ebe329a (origin/main, origin/HEAD) Update LAB_Template.md
89f82eb Update LAB_Template.md
2c788a3 Update LAB_Template.md
0852ba6 Update LAB_Template.md
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License```

```fd90139 (HEAD -> main, labreport) updated requirements
c6a26dd (origin/labreport) updated requirements
0d63669 My commit for fork of @trevorbunch lab
ebe329a (origin/main, origin/HEAD) Update LAB_Template.md
89f82eb Update LAB_Template.md
2c788a3 Update LAB_Template.md
0852ba6 Update LAB_Template.md
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License```

### A.3 Branch Repository
![Fork Relational Diagram](https://github.com/LAHardman/cis411_lab0_req/blob/main/assets/branchDiagram.png?raw=true)
### A.4 Extra Credit
![Fork Relational Diagram(1)](https://github.com/LAHardman/cis411_lab0_req/blob/main/assets/extraCredit.png?raw=true)

