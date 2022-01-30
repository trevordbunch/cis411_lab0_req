# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2022  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Tyler Regitz  
**GitHub Handle:** @ztigerR  
**Repository:** [Your Forked Repository](https://github.com/ztigerR/cis411_lab0_req) 
___

## 1. Overview

John Doe is a student at Messiah University and has brought to my attention a problem that he has been having weekly. "Do to my scheduale for Tuesday/Thurday classes I am unable to get food for lunch. This leaves me hungry till the dinning hall opens at 4:30." John is not the only student who has this problem, hundreds of students will find it very convient to have food deliever to their classrooms.

<br/>**This problem can be sloved with a few steps:**<br/>
* Modifiying the current online ordering system to accept input for building and classroom number.
* Hiring more students to complete deliveries for both Union and Falcon.
* Create an application/website to let the deliverer know when an order is ready.

Case Diagram:  
![Use Case](Lab1/../Images/Case%20Diagram.jpg)  
Credit: By Tyler Regitz


## 2. Requirements
- **Business**: The business objective that the system needs to satisfy.
  - B.1 The system must order the orders by room and building (Delivery Manager).
  - B.2 The system must track how many delivery students are avaliable for pick up (Union Manager).
  - B.3 The system must display the room number and building that the order is going to (Deleivery Manager).
  - B.4 The system must subract the appropriate amount of dinning dolars from the users account (Union Manager).
  - B.5 The system will accept the same payment methods that union/falcon accept (Falcon Manager).
  - B.6 The system must allow for slecting which order will be delivered and then removed when the delivery is completed (Delivery Manager).
  
- **User**: The actions that a user takes within the system
  - U.1 The user must enter a description of their person for the delieverer (Student 1).
  - U.2 The user must be able to select which business they are ordering from within the same application (Student 3).
  - U.3 The user can store prebuilt orders that have been saved to the user's account to be reordered quickly (John Doe).
  - U.4 The user must be able to order food to their dormbuilding(Woody).
  - U.5 The user can choose to leave a detailed comment for instuction on how to prepare the food (Derek).
- **Functional**: The functions should the system perform
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Hangry Student 2).
  - F.2 The system must display an interactive menu for both union or falcon depending on where the user wants to order from (Me).
  - F.3 The system must give an option for room number and building when delivery students are avaliable (Me).
  - F.4 The system will group orders together for combined delivery based on the size of the order, time it was ordered and location (Me).
  - F.5 The system will have a dropdown for fountain drinks (Me).
  - F.6 The system will have a dropdown for sauces and amount of each ordered (Me).
  - F.7 The system will only work with a messiah.edu domain (Me).
  - F.8 The system will ask the user to confirm before placing an order (Me).
  - F.9 The system will dispaly the users remaining account balance after a purchase using dinning dollars (Me).
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
  - N.2 The system must have two themes one for falcon and one for union to make it clear to the user which business they are ordering from (Student 4).
  - N.3 The system will support a dark mode (Student 2).
  
- **System**: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
  - S.2 The system needs to only support the rooms that have teachers who allow students to eat in their class (Proffesor 1).
  - S.3 The application must be branded with the messiah logo (Policy IT01.64).
  - S.4 The system must only be avalible when on the messiah secure wifi (Policy IT08.31).

 

## Appendix: GitHub Notes

### A.1 Forked Repository
![Use Case](Lab1/../Images/Repo%20Relationships.jpg) 

### A.2 Git Logs

**Labreport Log**



de39989  (HEAD -> labreport) 4th commit diagrams added<br/>
0a48f9e thrid commit requirements done<br/>
1d9bb4c second commit @trevordbunch<br/>
1dbdcd8 (origin/labreport) First commit @trevordbunch<br/>
50d40f8 (origin/main, origin/HEAD, main) Update references to main branch<br/>
ef962b1 Fix links in resource area<br/>
237b52e Update Instructions for template file<br/>
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1<br/>
6293806 Merge pull request #1 from mcjo163/main<br/>
7482f04 Typo in lab instructions<br/>
3080719 typo in readme<br/>
33efb41 formatted template<br/>


**Main Log**

42e3263 (HEAD -> main, labreport) commit 5<br/>
de39989 4th commit diagrams added<br/>
0a48f9e thrid commit requirements done<br/>
1d9bb4c second commit @trevordbunch<br/>
1dbdcd8 (origin/labreport) First commit @trevordbunch<br/>
50d40f8 (origin/main, origin/HEAD) Update references to main branch<br/>
ef962b1 Fix links in resource area<br/>
237b52e Update Instructions for template file<br/>
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1<br/>
6293806 Merge pull request #1 from mcjo163/main<br/>
7482f04 Typo in lab instructions<br/>
3080719 typo in readme<br/>
33efb41 formatted template


### A.3 Branch Repository
![Use Case](Lab1/../Images/Feature%20Branch.jpg)

