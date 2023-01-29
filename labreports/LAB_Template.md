# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Hope Tressler
**GitHub Handle:** hopetressler
**Repository:** https://github.com/hopetressler/cis411_lab0_req  
___

## 1. Overview


  
![Use Case Diagram](/assets/Assets.use.jpg)  


Actor(s): 
1. Client 
2. Catering Chef 
3. Catering Worker

Task(s):
1. Client views menu. 
2. Client places order. 
3. Client submits payment. 
4. Payment is processed. 
5. Catering Worker receives order and payment status. 
6. Catering Chef makes order.
7. Catering Worker delivers order.
8. Client confirms order is received. 

Information: 
1. Submitted data given by Client.
2. Data from ordering system specifying menu items, prices, services, dietary accomodations, etc. 

Outcomes: 
1. The client is able to place an order and submit payment. 
2. The catering worker can view order and submit it to catering chef(s). 
3. The order is delivered in a timely manner. 
4. The system accepts only the orders that catering is able to fulfill as described in system.

## 2. Requirements

Business Requirements: 
    B.1 The system must limit oreders based on the supply inventory so that the food ordered can be prepared. (Dining Services Manager)
    B.2 The system requires that orders are submitted 72 hours before desired delivery for food preparation. (Grace Taylor)
    B.3 The system will require confirmation of delivery from client and catering worker who delivers the order. (Madi Hoke)

User Requirements: 
    U.1 The user must provide a valid Messiah email address. (Grace Taylor)
    U.2 The user must provide a time and location on Messiah's campus. (Catering Worker)
    U.3 The user must be able to pay for the order using a valid credit/debit card or a Messiah University account. (Catering Worker)

Functional Requirements: 
    F.1 The system must render pages within 3 seconds. (Grace Taylor)
    F.2 The system must have protection of payment information via encryption. (Grace Taylor)
    F.3 The system must allow catering worker to view submitted order within 1 hour. (Catering Worker)

Non-Functional Requirements: 
    N.1 The system must run on mobile, laptop, and desktop devices. (Grace Taylor)
    N.2 The system must be up-to-date with the menu items and availability of order submissions. (Madi Hoke)
    N.3 The system must support 100 concurrent users. (Dining Services Manager)

System Requirements: 
    S.1 The system must be compatible with Messiah University's EMS event planning system. (Catering Worker)
    S.2 The system must require Messiah University's authentication. (Grace Taylor)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository

![Original vs Forked Repository](/assets/original_vs_forked.jpg) 

### A.2 Git Logs

Log for Step 2.7: 

8c1d844 (HEAD -> labreport, origin/labreport) first commit @trevordbunch 

Log for Step 6.4: 

56cea82 (HEAD -> main) Sections A.2 and A.3 complete 

### A.3 Branch Repository

![Main vs Feature Branch](/assets/main_vs_feature_branch.jpg)  

### A.4 Extra Credit

![Round Trip Diagram](/assets/round_trip_diagram.jpg)