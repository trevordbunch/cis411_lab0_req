# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Kyle Luce   
**GitHub Handle:** [kylebluce](https://github.com/kylebluce)    
**Repository:** https://github.com/kylebluce/cis411_lab0_req
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

## 2. Requirements

Business
-	B.1 The business must define an estimated delivery time for orders. These times can change between different hours of the day based on number of customers. (Union Manager)
-	B.2 The business must ensure that food can be prepared, packaged, and delivered in the expected delivery time. (Union Worker)
-	B.3 The business must have a delivery service in place where workers can take the food from the source to its destination in a safe and timely manner. (Kyle’s Roommate)
-	B.4 The business must designate delivery drivers and provide proper documentation and certification to be delivering on campus. (Union Manager)
-	B.5 The business must have a return system set up in case an order has a mistake or missed its delivery time.

User
-	U.1 The user must log-in with their Messiah University Credentials through the SSO portal through FalconLink. (Union Worker)
-	U.2 The user must select which on campus provider they are ordering from before selecting their order. (Union, Falcon, Café Diem)
-	U.3 The user must place their order using the menu from the online interface. (Union Worker)
-	U.4 The user must provide a location for where the food is to be delivered including a building name and room number. (Example Fry A204)
-	U.5 The user must specify when the order is to be delivered. They can choose between ASAP or pick a time later in the day. (Union Manager)
-	U.6 The user must be at the location at the time specified for delivery to receive their food. If they are not, the order will be taken back to the place they ordered from and will be available for pickup. (Union Manager) 

Functional
-	F.1 The system must have a menu for each of the on-campus food providers for the users to select between. (Union Worker)
-	F.2 The system must provide an order selection process for the student to choose what food they would like in their order.
-	F.3 The system must have an anticipated delivery time shown to the user prior to confirming the order. (Trevor’s Slides)
-	F.4 Once the order has been confirmed, the system will send the order to the workers making the food and the delivery person. (Union Manager)

Non-Functional
-	N.1 The system must render pages in less than 10 seconds after any user action or application event. (Trevor’s Slides)
-	N.2 The system must have an intuitive interface that allows for a positive customer experience.
-	N.3 The system must have a visually appealing interface.
-	N.4 The system must have contact information displayed on the website including a phone number of the food provider. (Union Worker)

System
-	S.1 The system must be available on Mac, Windows, Android, and iOS devices.
-	S.2 The system must be compatible with Google Chrome, Firefox, Safari, Microsoft Edge, Internet Explorer, and other browsers deemed necessary. (Tech Guy)
-	S.3 The system must keep user data such as login information confidential.
-	S.4 The system must adhere to PCI-DSS Security standards for payment with credit or debit cards.
-	S.5 The system should have policies in place for when the website goes down.
-	S.6 The system should be regularly kept up to date with updates and security standards as well as new features offered by the food provider.

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository

![ForkedRepositoryDiagram](/assets/cis411lab0drawing1.png)    

### A.2 Git Logs
2a56642 (HEAD -> labreport, origin/labreport) KyleLuce LabReport @trevordbunch    

### A.3 Branch Repository

![BranchDiagram](/assets/cis411lab0drawing2.png)     

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.
