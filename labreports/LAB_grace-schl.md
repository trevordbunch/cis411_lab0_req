# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Grace Schlauder  
**GitHub Handle:** grace-schl  
**Repository:** grace-schl/cis411_lab0_req  
___

## 1. Overview
The business problem that is being addressed is ordering a meal from an on-campus provider and having it delivered to a classroom.

The process starts with the user who places their order. The food order is recieved by the on-campus provider and then given to the chef. The chef cooks the food and sends out the cooked order. The cooked order is transferred over to a food assembly worker who makes sure each component of the order is there. The completed order is then ready for delivery. A delivery person takes the order and completes the delivery to corresponding user.


![Use Case Diagram](/assets/Use_Case_1.jpg)


## 2. Requirements
### Business

B.1.       The system must not allow delivery orders to be placed if the delivery would not be completed within 10 minutes after the food is prepared in order to maintain food quality (Michelle).

B.2.    The system must remove food options from the menu when supplies run out so that users are not ordering food they will not recieve (Jay).

### User

U.1.    The user must log into student account in order for the system to have access to meal payment plan (i.e. Falcon Dollars) (Nicole).

U.2.    The user must indicate which building and classroom they would like the order to be delivered to (Nicole).

### Functional

F.1.    The system must provide a time estimate of how long it will take for the order to be completed and delivered before the user completes the order (Michelle).

F.2.    The system must display the total cost of the order before the user completed the order (Jay).

### Non-Functional

N.1.    The system must load each page within 10 seconds after user interaction (Michelle).

N.2. The system must be easy to view and navigate for all users (Jay).

N.3. The system must be compatible for mobile users and computer users (Jay).

### System

S.1.    The system must have a way (i.e. file with list of all possible delivery locations) of validating that the building and classroom the user entered exists (Jay).

S.2. The system must use Messiah University Single Sign On (SSO) solution for the user to be able to validate their messiah.edu account and payment (Policy IT01.02) (Trevor Bunch).
 

## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repository](/assets/Forked_Repository_1.jpg)


### A.2 Git Logs
```
1001f48 (HEAD -> labreport) my commit @trevordbunch
50d40f8 (upstream/main, origin/main, origin/HEAD, main) Update references to main branch
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

```
5289fbc (HEAD -> main, labreport) first commit
1001f48 my commit @trevordbunch
50d40f8 (upstream/main, origin/main, origin/HEAD) Update references to main branch
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
![Feature Branch](/assets/Feature_Branch_1.jpg)
