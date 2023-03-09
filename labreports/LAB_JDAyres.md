# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Justin Ayres  
**GitHub Handle:** JDAyres   
**Repository:** https://github.com/JDAyres/cis411_lab0_req 
___

## 1. Overview
The business problem presented is, "I would like to order a meal from an on-campus provider, and have it delivered to my classroom". The problem is a method to deliver food to a student or faculty member from an on-campus provider.


Application Use Case Diagram:  
![Use Case](../assets/UseCaseDiagram.drawio.png)

Explenation:

The customer orders food which gets proccessed by our system, once this is complete the food order is confirmed by the chef who then cooks the food. The deliverer obtains the food and then deliveres it to the customer who then eats, and enjoys it... ideally.                   

## 2. Requirements
### Business 
B.1 The system must have a tipping feature for the worker, so that the customer can tip the deliverer (Student 4)

B.2 The system must be able to utilize a students dining dollar account to pay for the meal (Lottie Worker)

B.3 The system must not store any kind of payment card information (Student 5)

B.4  The system needs to help track how many orders a particular worker has fulfilled (Lottie Worker)
### User
U.1 The customer must provide their payment information to confirm the order (Student 5)

U.2 The customer needs to provide their school login in order to complete the transaction (Student 5)

U.3 The customer needs have a way to leave a review for the worker that delivered their food (Student 4)

U.4 The customer must be able to easily navigate which place they would like to order from and what they want from that location (Lottie Worker)
### Functional
F.1 The system must have a customer service review module (Student 2)

F.2 The system needs to be able to connect and operate off of Messiah's student login (ITS Worker)

F.3 The system must be able to handle large amounts of orders for peak hours (ITS Worker)

F.4 The system needs to be able to reach the desired order location in order to properly make the order (Student 3)
### Non-Functional
N.1 The system must have a miles per hour calculator so that the customer can see how fast the deliverer is moving (Student 4)

N.2 The system must have a module that shows the customer who is delivering their food (Student 3)

N.3 The system needs to have a way to give the student a time estimation on when their food will be delivered (Student 2)

N.4 The system must look aesthetically pleasing (Student 1)
### System
S.1 The system must be a mobile application and be accessible from Falconlink (Student 1)

S.2 The system needs to be compatible with Messiah's system (ITS Worker)

S.3 The system needs to meet Messiah's security standard (ITS Worker)

S.4 The system will have to ensure user safety as data is being transferred from location to location, eg. secure payment method (ITS Worker)



## Appendix: GitHub Notes

### A.1 Forked Repository
Diagram of the relationship between My repository and Trevor Bunch's repository:
![Diagram](/assets/Forking.drawio.png)

### A.2 Git Logs
Logs from 2.7: Creating A Feature Branch
```
828875c (origin/labreport) What's up @trevordbunch
50d40f8 Update references to main branch
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

Logs from 6.4: Merging the Feature Branch
```
2391ce6 Create MergingLogs.png
80ebb6d Merge branch 'labreport'
0373ceb (labreport) Da Vincis Notebook
d9b5d51 Shotgun Blues
f461a94 Add files via upload
faca882 Delete FeatureAndMainBranchRelationship.drawio.png
5a27185 Delete Forking.png
0f86074 Add files via upload
38fca83 Add files via upload
6cdc5da Delete Forking.drawio.png
12d31ac Add files via upload
828875c (origin/labreport) What's up @trevordbunch
50d40f8 Update references to main branch
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

### A.3 Branch Repository
Diagram of a relationship between a main branch and a feature branch:
![Diagram](/assets/FeatureAndMainBranchRelationship.drawio.png)
