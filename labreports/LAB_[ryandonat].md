# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2022  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Ryan Donat
**GitHub Handle:** ryandonat 
**Repository:** https://github.com/ryandonat/cis411_lab0_req.git 
___

## 1. Overview

Messiah does not have any food delivery service which delivers food from on-campus providers to classrooms. The system provides a medium to solve this problem:

![Use Case Diagram](/assets/Overview_Diagram.svg)  

In this system, users place orders to an on-campus food provider where the food will be made by employees and then delivered to a specified classroom. The order will be confirmed by employees and a confirmation/estimated delivery arrival time will be sent. Once the delivery employee arrives at the specified classroom, identification will be confirmed and the order will be delivered.


## 2. Requirements

In order to be sucessful, the system must fulfill a series of requirements. 

#### Requirements needed to satisfy business objectives (Buisness):
*   The system must limit orders based on staff availability so as Service Level Agreement of within 30 of promised delivery is not put in jeopardy (Boss)
*   The system must only provide food options which are currently available in each providers inventory. (Boss)
*   The on campus-providers must keep an accurate inventory of stock of food items and sold items in order to have accurate availability options. (Boss)
*   The system must keep an accurate and updated method of tracking what classrooms have classes or meetings so as not to disturb on-going classes or meetings.     (Thoughtful administration employee)

#### Actions users must take within the system (User):
*   The user must associate their account with a payment method (e.g., Falcon Dollars or Credit Card) 
*   The user must specify an available classroom with their order.
*   The user must be in the specified classroom within 2 minutes of system notice so that food is not left unattended or abandoned. 
*   The user must provide messiah ID associated with the account used to order the food upon arrival of delivery.

#### Functions the system must preform (Functional):
*   The system must present an anticipated delivery time prior to allowing the user to confirm the order (Student 1).
*   The system must present an updated anticipated delivery time when delivery is in transit (Sam Zercher - “Student 2”).
*   The system must only use food prepared at the time the time the order is placed as to keep food the correct temperature for delivery (Thomas Murray - "Student 3).
*   The system must provide users with a list of available classrooms to chose from (Boss)
*   The system should send two confirmation messages to user via text or online which details order + estimated delivery time, and when delivery employee is on route (Thomas Murray - Hungry Student 2).

#### Characteristics the system should have (Non-Functional):
*   The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
*   The system must be able to withstand high traffic surges so as to not slow down or become unavailable during common times of high volume food ordering i.e.breakfast, lunch, and dinner, end of class times, etc. (Concerned Introverted Server Administrator).

#### Specifications about how the system should be built (System): 
*   The system must use Messiah College Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
*   The sytem must comply to all PCI and MEssiah data security standards (Data Security Policy)
*   The system must be functional on all common display types (different browsers and IoT technologies)
*   The system must only be accessible to users who are currently connected to a Messiah trusted network. (Union and Falcon standard).


## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

#### System Constraints:
This system is only works with proper inventory and employee management, and will works under a few assumptions:
*   Messiah University providers already have working inventory systems which are updated live as product is sold.
*   Messiah University has a scheduling system which provides a database of classroom usage so that the availability of classrooms is documented.

#### Out of scope features/scalability:
This system has a few features that are out of scope for Messiah University, however given changes in resources could be implemented in the future by design.
*   Food/Orders from off campus providers in the area.
*   24/7 ordering availability
*   Custom order requests
*   Robotic delivery transport systems (Seen at larger unversities such as Pittsburg Unviersity)

## Appendix: GitHub Notes

### A.1 Forked Repository
  
![Use Case Diagram](/assets/Source_Repository_Relationship.svg)  

### A.2 Git Logs
Output of Git Logs pasted as follows:

393a99d (HEAD -> labreport) committed new .svg files after tracking them @trevordbunch
50d40f8 (origin/main, origin/labreport, origin/HEAD, main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License

### A.3 Branch Repository

![Use Case Diagram](/assets/Feature_Branch.svg)  
