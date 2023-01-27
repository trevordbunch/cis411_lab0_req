# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Ray Truex  
**GitHub Handle:** rt1252  
**Repository:** cis411_lab0_req  
___

## 1. Overview
The use cases for an application to solve the need “I would like to order a meal from an on-campus provider, and have it delivered to my classroom” are shown below:

![Use Case Diagram](/assets/food_use_case.png)

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

**Business**
- B1 - The system must ensure that orders can be delivered in less than 15 minutes (Brett Graff).
- B2 - The system will increase sales by removing barriers to purchase (chatGPT).
- B3 - The system will allow the company to collect delivery fees (Ray Truex).
- B4 - The system will reduce congestion during peak ordering hours (chatGPT).
- B5 - The system will allow the company to employee more employees as there will be a need for delivery people (Ray Truex).

**User**
- U1 - The user must be able to use the web or mobile app to place their order (Justin Ayres).
- U2 - The user must be able to include their building and room number on the checkout page (Brett Graff).
- U3 - The system must be able to allow users to store their favorite orders for easy re-ordering (chatGPT).
- U4 - The user must be able to choose their delivery time (Brett Graff).
- U5 - The user must be allowed to leave delivery instructions (Brett Graff). 

**Functional**
- F1 - The system must ensure that it only allows orders during the hours that the restaurant is open (Jon Wyrick).
- F2 - The system must keep up to date inventory levels to ensure that an order is not received for an item that is out of stock (Jon Wyrick).
- F3 - The system must be able to accept orders and automatically print a ticket of the order at the restaurant (Ray Truex).

**Non-Functional**

- NF1 - The system must send a notification to the user after delivery with an opportunity to leave feedback (Aidan Hubley).
- NF2 - The system must allow the user to see who is delivering their food and their mode of transportation (Shane Wahlberg).
- NF3 - The system may allow the user to see the average speed that the delivery person is moving at in MPH (Tim Kratz).
- NF4 - The system should allow the delivery person to take a proof of delivery picture (Brett Graff). 
- NF5 - The system should show the user a status bar of their food as it moves through the food creation lifecycle (Ray Truex).

**System**
- S1 - The system must allow users to use CAS to authenticate (Director of information security).
- S2 - The system must support MFA (Director of information security).
- S3 - The system must integrate with Humanity (shift tracking) to be able to see how many employees are at each restaurant, this ensures there are enough workers to keep up with the amount of orders (shift manager).
- S4 - The system must be able to shutdown for a set period of time when there are not enough employees or delivery people to keep up with the amount of orders (shift manager).

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

Step 2.7 logs
```
bf431f8 (HEAD -> labreport) Update LAB_rt1252.md
737c214 Update LAB_rt1252.md
cb410d1 name change
cca1671 Create food use case.png
7f42692 (origin/labreport) Hi @trevordbunch, I also like bbq
50d40f8 (upstream/main, upstream/HEAD) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
```

Step 6.4 logs


### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.