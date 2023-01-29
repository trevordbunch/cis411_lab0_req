# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Xavier Zepiora  
**GitHub Handle:** xzepiora
**Repository:** https://github.com/xzepiora/cis411_lab0_req
___

## 1. Overview
Add a use case diagram

**The business problem that needs to be solved is ordering food from Messiah's dining halls and having the meal delivered to a class room in a timely manner.**

Below is a short overview of who is involved, the actions being accomplished, the information needed, and the outcome.

- The people involved in the ordering process are the students that place the order, the meal prepper, and the delivery person. 
- The tasks that need to be completed are the student selects a dining hall, the student orders food, the student pays, the meal prepper recieves and completes the order, the delivery person delievers the food.
- The information needed for the functionality of the app are: student name, student order, student location, student payment info, menus, dining hall hours, and expected delivery time.
- The outcome of this is that the dining hall recieves payment and that the student recieves their order within a timely manner.

## 2. Requirements

**Business**

*B1* - Orders must be able to be fulfilled i.e. no out of stock food purchases. (Director of Food)

*B2* - The system will show the total price before confirming purchase. (Xavier Zepiora)

*B3* - The system must accept student dining dollars as a form of payment. (Xavier Zepiora) 

*B4* - Orders that will take long should notify a customer of that ahead of time. (Ray Truex)

**User**

*U1* - The user needs to be able to select the dining hall they want to order from. (Thomas Paine)

*U2* - The user needs to be able to view the menu of the dining hall they selected. (Thomas Paine)

*U3* - The user needs to be able to leave order notes such as allergies or if they want extra of something. (Director of Food)

*U4* - The user needs to be able to put their location in for delivery. (Thomas Paine)

*U5* - Users should be able to cancel an order within 5 minutes of purchase for a fee. (Xavier Zepiora)

**Functional**

*F1* - Location needs to be verified before the order tickets are made. (Megan Raab)

*F2* - Payment needs to be verified before order tickets are made. (Megan Raab)

*F3* - The system must encrypt PCI. (Allen Snook)

*F4* - Order tickets must print automatically once the order is apporved. (Ray Truex)

*F5* - The delivery person must be tracked. (Kevin Blimline)

- *F5.1* - The foood creation process should be tracked. EX: being prepared --> en route (Kevin Blimline)

*F7* - The system must allow previous order reordering. (Kevin Blimline)

*F8* - Orders must be printed with timestamps.

*F9* - Orders must only be allowed to be placed during dining hours.

**Non-Functional**

*N1* - The app should have webpage and mobile functionality. (App Developer)

*N2* - The app must work on different operating systems. (App Developer)

*N3* - The app should have clear User Interface (UI) and clear workflow (Kevin Blimline)

**System**

*S1* - The system must authenticate through the Messiah CAS system. (Allen Snook)

*S2* - The system must have easily scalable data storage for user information. (Kevin Blimline)

*S3* - The system must be made on React Native that way it has cross platform capabilities. (Andrew Gromenko)

## 3. Assumptions
1. All users on the app are Messiah Students as only student dining dollars are accepted.
2. The app will only be used when school is in session.
3. Users will not be ordering food to their dorm rooms.

## Appendix: GitHub Notes

### A.1 Forked Repository

![Forked Repository](./Images/Lab%20Requirements%20(3).jpg)

### A.2 Git Logs


**2.7 Logs**
```

043cfd2 (HEAD -> labreport, origin/labreport) Update LAB_xzepiora.md

295c8be @trevordbunch

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


**6.4 Logs**

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

![Branch Repository](./Images/Branch%20Making.jpg)

