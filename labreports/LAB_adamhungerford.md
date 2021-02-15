# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Adam Hungerford  
**GitHub Handle:** [adamhungerford](https://github.com/adamhungerford)  
**Repository:** https://github.com/adamhungerford/cis411_lab0_req  
___

## 1. Overview

![Use Case Flowchart](/assets/overviewflowchart.png)

"I would like to order a meal from an on-campus provider, and have it delivered to my classroom."
The basic goal of this problem is to move food from an on-campus provider to a classroom. This entails some form of application allowing the user to order (ideally, an aggregate of the online ordering apps for each on-campus service provider), authenticated using CAS, and which gives the user the ability to pay in-app with Dining Dollars, Falcon Dollars, or credit or debit. 

Once the user has placed their order, flow proceeds to the chefs, who will receive the order by way of the ticket system used in each on-campus provider. Delivery orders will be marked with a large-font "Delivery" heading at the top of the ticket, with the educational building specified in a subheading underneath. When the chefs have completed the order, it will be given to the delivery personnel.

Delivery personnel must take the food to the classroom (or nearest lobby in building) within five minutes (about the time it would take to walk there oneself). If delivery personnel are overtaxed, delivery orders must be limited. 


## 2. Requirements

- **Business:**
	- B.1 Stress on the system must not lengthen the wait of sit-in customers. (Matt)
	- B.2 Delivery orders must be limited by flexibility of delivery workers. (Matt)
- **User:**
	- U.1 The user must be able to pay with Falcon Dollars, Dining Dollars, or credit. (Very Hungry Person)
- **Functional:**
	- F.1 The service will provide an aggregate of menus from each on-campus provider. (Drew)
	- F.2 The service must be integrated with the ticket system used in each on-campus provider, and must print "Delivery" and the location on the tickets. (Drew)
- **Non-functional:**
	- N.1 Food must be delivered before the approximate time it would take for the client to walk to the on-campus provider. (Matt)
- **System:**
	- S.1 User authentication must be provided through Messiah CAS. (Marissa)


## 3. Assumptions
There are 3 on-campus providers: Lottie Nelson Dining Hall, Larsen Student Union, and The Falcon.
- Orders at The Falcon is only open until 2:30. 
- Larsen Student Union is the furthest from the educational buildings, except perhaps Jordan-Kline.

Some workers must become delivery personnel, unless additional workers are hired.

## Appendix: GitHub Notes

### A.1 Forked Repository

![Forked Repository Diagram](/assets/gitdiagram.png) 

### A.2 Git Logs

#### 2.7 Log
`892ce11 (HEAD -> labreport, origin/labreport) Added lab report @trevordbunch
ef962b1 (upstream/main, origin/main, origin/HEAD, main) Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License`

#### 6.2 Log
`52fd59b (HEAD -> labreport) Further edited lab report @trevordbunch
892ce11 (origin/labreport) Added lab report @trevordbunch
ef962b1 (upstream/main, origin/main, origin/HEAD, main) Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License`

### A.3 Branch Repository

![Relationship Diagram](/assets/featurebranch.png)

### A.4 Extra Credit

![Round-trip Diagram](/assets/roundtripdata.png)