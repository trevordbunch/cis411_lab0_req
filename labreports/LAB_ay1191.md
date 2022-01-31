# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Azianna Yang  
**GitHub Handle:** ay1191  
**Repository:** (https://github.com/ay1191/cis411_lab0_req.git) 
___

## 1. Overview
The process begins with a client placing an order. Once he makes the payment, the manager confirms the order. After the manager confirms, he sends the order to the chef. The chef then cooks the food. When the cook finishes, he gives the cooked food out for delivery. Once it's out for delivery, the delivery man gets the cooked food and delivers food to the client. The client then receives the food.

![Business Diagram](/assets/Business.svg)


## 2. Requirements
Busines
B.1 The system must limit orders based on staff capacity, so that
deliveries are met (Straight Hair Boss). 
B.2 The system must only display the food available 
(Pointy Hair Boss).

User
U.1 The user must associate their account with payment 
method(e.g. Falcon Dollars or Credit/Debit Card) (Student 1).

Functional
F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Student 2).
F.2 The system must only confirm the order if there is a payment made (Student 3).

Non-Functional
N.1 The website pages should load in 3 seconds with the total number of simultaneous users <5 thousand (UX Expert Lady).
N.2 The system should be able to handle 1,000 users without performance deterioration (UX Expert Lady).

System
S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu doman 
(Policiy 101.03).

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

![Repository Diagram](/assets/Overview.svg)


### A.2 Git Logs

``
ddf9ba5 (HEAD -> labreport, origin/labreport) Images
15db8f8 your commit and reference @trevordbunch in the message
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

``

``

ddf9ba5 (HEAD -> main, origin/labreport, labreport) Images
15db8f8 your commit and reference @trevordbunch in the message
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


``

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

![Branch Repository Diagram](/assets/Branch_Relationship.svg)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.