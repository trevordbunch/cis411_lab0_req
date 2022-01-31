# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Gloria Houngbeke 
**GitHub Handle:** GlorKemH 
**Repository:** Your Forked Repository  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

Problem: The delivery staff is unable to deliver to the client.

This business process is an example of a user/client about to order. The client must access the ordering through the messiah app on their phone or through any convient messiah provided app near by. 
The task is for the user to select their desired items and place it in their cart. Once the user has finalized their choices, they are to provide their location and payment plan.
Once the kitchen receives the desired item. They will prepare the item step by step while notifying the delivery staff through each step. 

Once the food have been prepared the delivery staff will notify the client.

The delivery staff will head to the stated destination. Once the delivery staff leaves their original location, the client will be charged for the items and delivery through the provided payment method.

Here is an image of the bussiness process to address this problem:

(/Users/gloriahoungbeke/Desktop/Ghelp/cis411_lab0_req/labreports/Overview.pdf)



## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

Course: CIS 411, Spring 2022
Instructor(s): Trevor Bunch
Name: Gloria Houngbeke 
GitHub Handle: GlorKemH
Repository: GlorKemH/cis411_lab0_req

Overview:
Problem: The delivery staff is unable to deliver to the client.


Single Request: “I would like to order a meal from an on-campus provider and have it delivered 
to my classroom.”

Requirement:
Business: The business objective that the system needs to satisfy.
B.1 The food provided shall have the following item ready within a 20 minute time clock. The quality of food depends on the amount of time each staff is given. The delivery system will be in contact with the staff within each step of the food-making process.
B.2 The system must limit orders based on staff capacity so that the delivery Service Level Agreement within 10 of promised delivery is not placed in jeopardy.
B.3 The system and user must have a consistent interaction throughout the whole process. The student must be present in the classroom while the item is being delivered. The delivery guide 

must scan the student-issued ID to show the student was present at the time of delivery. The system must charge the student at the time of delivery.

User: The actions that a user takes within the system
U.1 The user needs to fill in their information within the ordering system application.
U.2 The user must associate their account with the payment method(e.g., Falcom Dollars or Credit Card)(Hungry Student 1).
U.3 The user will have sufficient dining dollars in order to use the system. Charges will be made to the account if the student is not present during the delivery process.

Functional: The functions should the system perform
F.1 The system must present an anticipated delivery time before allowing the user to confirm the order (Hangry Student 2).
F.2  The system must present the total price of each item throughout the selection process for the user and present the total amount at the end with options of email, paper receipt. 
F.3 The system must present an anticipated cooking time before allowing the delivery system.
Non-Functional: The characteristics that the system should have.
N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
N.2 The system must stay awake during the user’s interaction.
N.3 The system must refresh every 30 seconds after each user’s input.
N.4 The system must present recommendations to users when a user is unable to make a decision within 15 seconds.

System: Specifications about how the system should be built.
S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
S.2 The system should be available on all platforms and only to messiah students.
S.3 The system should be able to run during traffic/busy hours.






## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

(/Users/gloriahoungbeke/Desktop/Ghelp/cis411_lab0_req/labreports)



### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

gloriahoungbeke@Glorias-MacBook-Air cis411_lab0_req % git log --oneline
983df3e (HEAD -> main, labreport) I' am commited.
0757078 (origin/labreport) Commited @TrevorBunch
50d40f8 (origin/main, origin/HEAD) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
gloriahoungbeke@Glorias-MacBook-Air cis411_lab0_req % 




### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)



(file:///Users/gloriahoungbeke/Downloads/Untitled%20drawing.svg)



### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.