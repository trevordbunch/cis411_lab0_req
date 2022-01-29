# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Reid Burger
**GitHub Handle:** [ReidBurger](https://github.com/ReidBurger)
**Repository:** Reid's Forked Repository  
___

## 1. Overview
The main problem I am trying to solve is as follows: “I would like to order a meal from an on-campus provider, and have it delivered to my classroom.” I have interviewed two people, one is a teacher, and the other is a student. The teacher, Dr. Malarky, is male, 46 years old, and has three children. He says that an app that provides such a service should do so quickly and in a cost-effective way. Also, the interface should be intuitive so that he can order while walking to class or while being distracted by those pesky students. 

The second person, Paul Callender, who is 20 years and male, says that an app with such power should be able to also cater to dorms in addition to classrooms and students should be able to sign up to deliver rather than just be the recipient. He also says that the delivery fee should not be too expensive or it would prevent most college students from using it.

The third person, Sydney White, who is 21 years and female, says that as a Union worker, the orders should come in like any other online order and not be separate, and that orders should be put on hold when the queue is full or the workers are strained. Also, she says that she shouldn't have to interact with the app at all while she's working and it should be up to the deliverer to confirm and pick up the order.

![Use Case Diagram](/assets/Lab0_UseCases.svg)

## 2. Requirements
- **Business**
  - B.1 The system must not charge more than 50% of the base price of the food for delivery services (Paul)
  - B.2 The system should limit incoming orders or provide a warning to users when it is detected that there are more than 20 orders in queue. (Sydney)
- **User**
  - U.1 The user must be able to order food in less than one minute (Dr. Malarky).
  - U.2 The user should have payment info saved to make transactions faster (Dr. Malarky)
  - U.3 The interface must be easy to interact with and buttons must be obvious and intuitive (Dr. Malarky)
- **Functional**
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Dr. Malarky).
  - F.2 The system must allow students to deliver for other students (Paul)
  - F.3 The system must tell delivery workers where to pick up the food and the estimated time (Paul)
- **Non-Functional**
  - N.1 The system must render pages in less than 10 seconds after any user action or application event. (Dr. Malarky)
  - N.2 The system must be intuitive with less than 10 different kinds of buttons per screen
  - N.3 The system must be made such that only the delivery person and the client need to interact with it. (Sydney)
- **System**
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
  - S.2 The system must push orders through the same process Messiah has so that orders get to cooks in the same way. (Sydney)

## 3. Assumptions
Another option for this app is to send users to the Messiah website for online ordering (if ordering through the Falcon or Union) so that we don't have to store card information or worry about using SSO and sending it through the same system Messiah has. 

This app could be split into two, with a user app only for placing orders and paying, and a second app for delivery workers to receive, pick up, and deliver orders.

If we are creating one app for everything, there should be a clear switch from "Worker Mode" to "Customer Mode" so that users aren't confused. 

## Appendix: GitHub Notes

### A.1 Forked Repository
![Diagram 1](/assets/git_diagram1.png)

### A.2 Git Logs

```
e667267 (HEAD -> labreport, origin/labreport) Try Again @trevordbunch
```

```
7239260 (HEAD -> main) Merge branch 'labreport' into main
b970e7b (origin/labreport, labreport) The Last Push @trevordbunch
5cee702 Final Push @trevordbunch
bd525b1 Diagrams @trevordbunch
550ab93 Added Requirements @trevordbunch
fed3ceb StackOverflowGodsSmileUponMe @trevordbunch
f5f125d DoIt @trevordbunch
aaef139 I hate images @trevordbunch
cc37496 AHHH @trevordbunch
f0b12df Please Work@trevordbunch
57cf313 NowWork @trevordbunch
1427e15 TryAgain @trevordbunch
fdf6a37 UseCaseDiagram @trevordbunch
995a425 Part1 @trevordbunch
e667267 Try Again @trevordbunch
50d40f8 (origin/main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
```

### A.3 Branch Repository
![Diagram 2](/assets/git_diagram2.png)

### A.4 Extra Credit
![Diagram 3](/assets/git_diagram3.png)