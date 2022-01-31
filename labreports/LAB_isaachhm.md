# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Isaac Ho
**GitHub Handle:** isaachhm  
**Repository:** https://github.com/isaachhm/cis411_lab0_req.git 
___

## 1. Overview
The use case diagram below shows the business process of delivering food to a student. Ther are four actors, the client, the cook, the delivery person, and the boss. The client accesses the system and places their order. The client must also input the classroom and building they want to food to be delivered to. After the order is submitted, it gives the total amount that the student needs to pay and the students account is charged. The order confirmation is then sent to the cook. The food is then cooked by the cook and given to the delivery person. The delivery person must then deliver the food to the assigned classroom in the assigned building. The client must be in the assigned classroom 5 minutes before the delivery person arrives.

![Use Case Diagram](/assets/Business.svg)  


## 2. Requirements
1.	Business
- The system must limit the amount of orders based on staff capacity in order to deliver within 10 minutes. (Pointy Hair Boss)
- The system must only display the available foods. (Pointy Hair Boss)
2.	User 
- The user must associate their account with payment method. (Hangry Student 1)
- The user must put their classroom number and building before submitting the order. (Hangry Student 1)
3.	Functional
- The system must present the total amount that the order costs. (Hangry Student 2)
- The system must only send an order confirmation after the student makes the payment. (Pointy Hair Boss)
- The system must present an estimated delivery time before allowing the student to confirm their order. (Hangry Student 2)
- The system must notify the student through an email when the delivery is in transit and an updated delivery time. (Hangry Student 2)
4.	Non-Functional 
- The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
- The system must be available for students to access between opening time and closing. (Pointy Hair Boss)
- The system must be able to withstand high network traffic in the case of many students ordering at the same time. (UX Expert Lady)
5.	System 
- The system server must use Messiah’s Single Sign On solution for any accounts with the messiah.edu domain. (Policy IT01.02)
- The system must be user friendly and easy to navigate. (Hangry Student 1)

## Appendix: GitHub Notes

### A.1 Forked Repository
![repository](/assets/repo_diagram.svg)

### A.2 Git Logs
b7882dc (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
cbfbd87 your commit and reference @trevordbunch in the message
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

### A.3 Branch Repository
![Branches](/assets/Branches.svg)
