# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Timothy Lee   
**GitHub Handle:** timothymlee  
**Repository:** [Forked Repository](https://github.com/timothymlee/cis411_lab0_req) 
___

## 1. Overview
**User Statement of Need**:     
“I would like to order a meal from an on-campus provider, 
and have it delivered to my classroom."

**Use Case Name**:  
Campus Food Delivery    

**Description**:    
A Messiah University student or faculty member desires to have food delivered to their classroom from on-campus dining options. The user enters their order, pays for the food, and specifies a delivery location. 

**Trigger**:    
A user enters an order.   

**Preconditions**:
- The user is a Messiah University student or faculty member.
- The ordered items are available at the on-campus dining options.  
**Normal Course**:
- User enters order and pays for food.
- The order is prepared and packaged.
- An employee delivers the food.

**Use Case Diagram**:   
![Forked Repository Diagram](/assets/Lab0Part4_Diagram.svg) 


## 2. Requirements

- **Business**: The business objective that the system needs to satisfy.
  - B.1 The system must limit orders to products available at on-campus prodivers each day. (Matt Fisher)
  - B.2 THe system must limit payment methods to accepted types, as well as validate them. (Miggy Matanguihan)
  - B.3 The system must be limited to users within Messiah University. (Manager)
- **User**: The actions that a user takes within the system.
  - U.1 The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card). (Hungry Student 1)
  - U.2 The user must associate their schedule with the system to automatically specify a default delivery location. (Miggy Matanguihan)
- **Functional**: The functions should the system perform.
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order. (Hungry Student 1)
  - F.2 The system must present a purchase summary prior to confirming the order. (Matt Fisher)
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
  - N.2 The system must hold current orders for 10 minutes before automatcally logging-off the user. (Student 2)
- **System**: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
  - S.2 The system must show recent orders for convenience and to ensure a second order is accidentally made (Student 2)

## 3. Assumptions
This product will be website based and similar to the Union and Falcon ordering systems already integrated at Messiah University.

## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repository Diagram](/assets/Lab0Part1_Diagram.svg) 

### A.2 Git Logs
**Step 2.7 Log**
```
C:\Users\timot\Documents\College\Messiah\3rd Year\Spring 2022\CIS 411\Labs\cis411_lab0_req>git log --oneline
c719351 (HEAD -> labreport, origin/labreport) Commit Round2 Attemp1 Step2 for @trevordbunch
50d40f8 (origin/main, origin/HEAD, main) Update references to main branch
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

**Step 6.4 Log**
```
C:\Users\timot\Documents\College\Messiah\3rd Year\Spring 2022\CIS 411\Labs\cis411_lab0_req>git log --oneline
8dd93af (HEAD -> main, origin/labreport, labreport) Commit Round2 Attemp1 Step2a
c719351 Commit Round2 Attemp1 Step2 for @trevordbunch
50d40f8 (origin/main, origin/HEAD) Update references to main branch
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
![Branch Repository Diagram](/assets/Lab0Part2_Diagram.svg)  


### A.4 Extra Credit
![Round-trip Diagram](/assets/Lab0Part8_Diagram.svg)    