# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2023  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Joseph McGillen  
**GitHub Handle:** [jm1959](https://github.com/jm1959)  
**Repository:** [jm1959/cis411_lab0_req](https://github.com/jm1959/cis411_lab0_req)
___

## 1. Overview
Employee's would like to order a meal from an on-campus provider, and have it delivered to my classroom.

![Use Case Diagram](/assets/UseCase.svg)
Credit: By Joseph McGillen

1. Employee: Signs into application using Messiah account and creates a order and selects 
   a payment method and class room for food to be delivered to
2. Chef: Recieves order from employee and prepares the food
3. Cashier: Recieves notification that the order has been payed for
4. Delivery Person: Picks up food from the chef and delivers food to designated classroom 
## 2. Requirements
- Buisness: The business objective that the system needs to satisfy
  - B.1 The system must be able to limit orders based off of staff copacity (Union Manager)
  - B.2 The system must notify students when items are no longer available on the menu (Union Manager)
  - B.3 The system must operate on the same schedule as the dining services (Union Manager)
- User: The actions that a user takes within the system
  - U.1 The user must associate a payment method with their account (Devin Hutcheson)
  - U.2 The user must choose a location to order from (Devin Hutcheson)
  - U.3 The user will be able to track orders and delivery times (Devin Hutcheson)
- Functional: The functions should the system perform
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Nate Morse)
  - F.2 The system must remeber food allergies that users enter into the system (Nate Morse)
  - F.3 The system must allow the user to choose from multiple locations to order food (Nate Morse)
- Non-Functinonal: The characteristics that the system should have
  - NF.1 The system must render pages in less than 1 second (Webpage Expert)
  - NF.2 The system must show all menu options visably on one page (Dining Services)
- System: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) 
  - solution for any accounts with a messiah.edu domain. (MessiahIT 0102)
  - S.1 The system must be able to operate on desktops, laptops and mobile devices (MessiahIT 0205)
## 3. Assumptions
-Constraints
  -Time: The system must only be operating during the working hours of the dining services
  -Distance: The system must operate withing the Messiah University campus
  -Weather: If weather condidtions are deemed to hazerdous the system should not be processing orders
## Appendix: GitHub Notes

### A.1 Forked Repository
Relationship between source repository and personal repository
![Use Case Diagram](/assets/Forked_Repositroy.svg)
Credit: By Joseph McGillen
### A.2 Git Logs
Step 2.4
```
0d0d996 (HEAD -> labreport, origin/labreport) LAB commit
c453bd5 Delete LAB_jm1959
17fb595 Create LAB_jm1959
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
Step 6.4
```
8e427c8 (HEAD -> labreport, origin/labreport, main) Update LAB_jm1959.md
0d0d996 LAB commit
c453bd5 Delete LAB_jm1959
17fb595 Create LAB_jm1959
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD) Update references to main branch
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
Relationship between main branch and feature branch
![Use Case Diagram](/assets/Branch_Repository.svg)
Credit: By Joseph McGillen