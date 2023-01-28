# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2023  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Michael Shoul  
**GitHub Handle:** [m-shoul](https://github.com/m-shoul)  
**Repository:** [m-shoul / cis411_lab0_req](https://github.com/m-shoul/cis411_lab0_req)  
___

## 1. Overview
Students at Messiah University want to be able to order a meal from an on-campus provider and have it delivered to a classroom location.

To solve this issue, we are going to build an application that will be able to handle the following process:
1. The student visits the online ordering platform or mobile application provided by Messiah University.
2. The student selects menu items and specifies the delivery location.
3. The student makes a payment using a preffered method such as Falcon Dollars, debit/credit, or mobile payments.
4. The system confirms the order and provides an estimated delivery time.
5. The cook prepares the order and delivery personnel brings the meal to the specified location. 

![Use Case Diagram](/assets/CaseDiagram.svg)  
Credit: Michael Shoul

## 2. Requirements
### 2.1 Business
* B.1 - Capability: The system must have an online platform or mobile application for students to place their orders and make payments. (Ben Clarke)
* B.2 - Order Tracking: Students must have the ability to track their orders in real-time and recieve updates on the status of their delivery. (Busy Student)
* B.3 - Feasibility: The system must be able to limit orders based on staff capacity at all locations on Campus. (Dining Services)
* B.4 - Delivery: The system must have the ability to deliver meals within 15 minutes after the food has been prepared. (Ben Clarke)
* B.5 - Options: The system will offer a variety of meal options to accomodate for dietary restrictions and allergies.

### 2.2 User
* U.1 - Options: The user must have access to a variety of meal options, including options for dietary restrictions and allergies. (Health Expert)
* U.2 - Payment: The user must be able make payments securely, with multiple options available such as Falcon Dollars or credit/debit. (Dining Services)
* U.3 - Convienence: The user must be able to place an order and have it delivered to a specified location with minimal waiting time. (Ben Clarke)
* U.4 - Order Tracking: The user must be able to track their order and recieve updates on the expected delivery time. **SOURCE**
* U.5 - User Interface: The user must be able to navigate the ordering process easily and with minimal confusion. **SOURCE**

### 2.3 Functional
* F.1 - Online System: The system must allow customers to place their orders online, including selecting menu items, speficying delivery locations, and making payments. **SOURCE**
* F.2 - Payment: The system must be able to securely process payment from students using Dining Dollars, Ala Carte, credit/debit cards, or mobile payments. (Ben Clarke)
* F.3 - Inventory: The system must be able to track and update inventory, ensuring that menu items are available for students to order. (Joe McGillen)
* F.4 - Reciept: The system must send an email reciept subsequent to the online transaction. (Credit Card User)
* F.5 - Delivery: The system must provide an anticipated delivery time prior to allowing the user confirm the order. (Joe McGillen)
* F.5 - Delivery Management: The system must be able to track the location of the delivery personnel to ensure orders are delivered to the correct location on campus. **SOURCE**
* F.6 - Feedback: The system must have a way to handle customer issues and recieve feedback to improve future performance. **SOURCE**

### 2.4 Non-Functional
* N.1 - Speed: The system must be able to handle a high volume of orders and respond to student requests quickly and efficiently. **SOURCE**
* N.2 - Reliability: The system must be available to students at all times with minimal downtime for maintenance. **SOURCE**
* N.3 - Maintainabilty: The system must be easy to maintain and update, with clear documentation for troubleshooting. **SOURCE**
* N.4 - Security: The system must have security measures in place to protect student data and adhere to Messiah regulations. **SOURCE**
* N.5 - Accessibility: The system must be accessible to all users, including those with disabilities.**SOURCE**
* N.6 - Performance: The system must render pages within 1 second of any event or user application. **SOURCE**
* N.7 - Integration: The system must be able to integrate with other systems and services provided by Messiah University. **SOURCE**
 
### 2.5 System
* S.1 - Hardware: The system must be able to run on a variety of devices, such as desktop computers, laptops, and mobile devices. **(SOURCE)**
* S.2 - Scalability: The system must be able to handle a high volume of orders.**(SOURCE)**
* S.3 - User Interface: The systems must have a user-friendly user interface to easily navigate the ordering process and track their orders. **(SOURCE)**
* S.4 - Network: The system must use Messiah University Single Sign On (SSO) for any accounts with a messiah.edu domain. **SOURCE**
* S.5 - Security: The system must have robust security measures in place to protect student data and adhere to Messiah University standards. **SOURCE**

## 3. Assumptions

### 3.1 Constraints
* C.1 - Time: The service will only allow deliveries within operating hours of on-campus providers.
* C.2 - Location: The service will only be available to students located at the Grantham campus location.
* C.3 - Capacity: The application can only handle a certain number of orders at a time.
* C.4 - Weather: The service may not operate during inclement weather.
* C.5 - Fees: The service will have a delivery fee factored into the total cost of the order.

### 3.2 Scope
* S.1 - Delivery: The service will only allow students, faculty, and staff, to order meals from on-campus providers.
* S.2 - Authorization: The service will verify the identities of users to ensure only authorized individuals can place orders.

### 3.3 Caveats
* CV.1 - Staffing: The service will require a sufficient number of deliverty employees to handle the volume of orders.
* CV.2 - Tracking: The serivce will have to use specific technologies to track the delivery.


## Appendix: GitHub Notes

### A.1 Forked Repository

![Forked Repository](/assets/ForkedRepo.svg)  

Relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and my [forked repository](https://github.com/m-shoul/cis411_lab0_req). 

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

**WHAT DO I DO HERE**

Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
![Branch Repository](/assets/FeatureBranch.svg)
Relationship between my [main branch](https://github.com/m-shoul/cis411_lab0_req/tree/main) and my [feature branch](https://github.com/m-shoul/cis411_lab0_req/tree/labreport) in my repository.

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.