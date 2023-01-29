# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Jeff Sinsel  
**GitHub Handle:** JeffSinsel  
**Repository:** https://github.com/JeffSinsel/cis411_lab0_req
___

## 1. Overview
- The people involved are a Customer, Chef, Delivery Person, and possibly a cashier. 
- The tasks involve ordering, paying, getting, and delivering food. 
- The information need is the student's method of payment, room that they wish to pick up the food, and the actual order.
- The outcomes are that the student receives their food in a timely manner or their order gets rejected for having a bad payment source.

![Business Graphic](/assets/businessGraphic.PNG)

## 2. Requirements
- **Business**: The business objective that the system needs to satisfy.
  - B.1 Existing ordering systems will be implemented to save on development costs (Project Manager administrator Officer Director).
  - B.2 The system must restrict orders so that the staff can handle the deliveries (Project Manager administrator Officer Director).
- **User**: The actions that a user takes within the system
  - U.1 The user must sign into their Messiah account before ordering (Hungry Student 1).
  - U.2 The user must verify the location they want the food delivered (Hungry Student 2). 
- **Functional**: The functions should the system perform
  - F.1 The system must display the hours of operation of the different on-campus facilities (Hangry Student 2).
  - F.2 The system must allow for students to order 30 minutes ahead of time, if staff are available (Hangry Student 1).
  - F.3 Delivery fees must be calculated and added so that delivery staff can be properly paid (Project Manager administrator Officer Director).
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The location of the delivery must be accessible by the person delivering the food. (Delivery Person)
  - N.2 The system must be able to handle the server load from meal rushes allowing up to 1000 students to access the application at a time. (UX Expert Lady)
- **System**: Specifications about how the system should be built.
  - S.1 The system must be an application available in both the Apple app store and the Google Play Store. (Tech Person 1)
  - S.2 The system must be able to access your location to verify the orderer is on campus. (Tech Person 1)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.

1. Orders will be rejected if the is not sufficient fund in the account used to order.
2. Deliveries are made only to on-campus indoor spaces.
3. The food is expected to be delivered in a reasonable amount of time. 

## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repository Diagram](/assets/forkedRepositoryGraphic.PNG)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.
### 2.7
```
56d3062 (HEAD -> labreport, origin/labreport) yo @trevordbunch
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD, main) Update references to main branch
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
### 6.4
```

```
### A.3 Branch Repository
![Branch Diagram](/assets/branchOffMainGraphic.PNG)

### A.4 Extra Credit
Sent a pull request fixing typos