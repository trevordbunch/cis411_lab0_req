# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Rachel Beattie
**GitHub Handle:** Your GitHub Handle  
**Repository:** [Your Forked Repository](https://github.com/R-B1509/cis411_lab0_req)  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

Business Need: “I would like to order a meal from an on-campus provider, 
and have it delivered to my classroom."
**Actors**
  A.1 Client: Orders food, Pays for food
  A.2 Deliverers: Deliver Food
  A.3 Chefs: Cooks Food
**System Tasks**
T.1 Ordering food from System
T.2 Link account information, confirm location and give estimated delivery time
T.3 Confirm Order by customer and system
T.4 Order recorded in system
T.4 Payment transaction confirmation
T.5.1 Order information to chef
T.5.12 Payment information to a separate financial system
T.5.13 Location details given to delivery person
T.6 Delivery of food within estimation of time to specified location
**INFO**
T.3.1 Backfeed of safety check of area hazards and possible allergans i.e. No food in a chemistry lab, art studios due to toxic paints, biology/nursing/health with autopsy due to sanitation,physics, basically any sort of lab, disruption
T.5.2 Update information on provisions each time an Order is fufilled but before Delivery
**Outcomes**
O.1 Confirmation of transactions
O.2 Delivery of food
O.3 Financial updates to seperate system
O.4 Update information on supplies

![Simple Diagram](https://app.diagrams.net/#G1FeSquaX99_ltCL5PJ2VPnXg6ZAtJvSji) 

Here is an example of including a image into your lab report using a URL:  
![Use Case](https://commons.wikimedia.org/wiki/File:Use_case_restaurant_model.svg#/media/File:Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

Here is an example of including a image into your lab report using an uploaded file:  
![Use Case Diagram](/assets/Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.
 **Business**: Business Objective of system
    B.1 Deliver Food in estimated time
    B.2 Ensure safety of students and faculty
 **User**: Client-side interaction
    U.1 User Account must be associated with payment method, i.e. Falcon Dollars, Credit Card (lessonsLearned.md File Example)
 **Functional**: The functions the system should perform
    F.1 The system must present a precise delivery time prediction prior to allowing the user to confirm the order to help ensure that they will be at the location given ("Hangry Student 2" from lessonsLearned.md File Example, co-worker at Lotties).
    F.2 Resources must be updated after every confirmation of Order and Payment (Self)
    F.3 Check for constraints before final confirmation of Order on the System's side (Self)
 **Non-Functional**: The characteristics that the system should have.
    N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady, lessonsLearned.md File Example)
    N.2 The system should update any changes in food stock on Business End (Self)
    N.3 Any food allergy items list ingredients in order form (Self, Faculty-Member)
 **System**: Specifications about the build
    S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
    S.2 There must be a prior agreement with the classroom's professor before the any order is confirmed that allows for food delivery (Faculty Member)
## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  
 **Constraints**
  C.1 No food is allowed to be delivered to Hazard Zones, i.e. Science Labs, classes with Chemical Usage, Art Studios due to toxic paints (Co-worker)
  C.1.1 No food allowed in food labs for academic integrity (Faculty Member)
  C.2 There must be a prior agreement that allows for food delivery with the classroom's professor before any confirmation message is sent to the student confirming their order (Faculty Member)
  C.3 Double check the class attendance where food is delivered to for any extreme food allergy, as in, flare-up if allergen is just touched or nearby (Faculty Member)
  C.3.1 Food Allergens listed in Menu description of food (Self, from discussion with Faculty-Member)

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  
[Diagram](https://app.diagrams.net/#G1RKvuqzau33citIMrWbnYxsMjq2FHRlh4)
### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.
c0fd557 (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
31683a9 (origin/main, origin/HEAD, main) Update LAB_INSTRUCTIONS.md
c05d49a Merge pull request #79 from JeffSinsel/typoFix
301ee3e Update LAB_INSTRUCTIONS.md
20e50ed fixed typos
1ac4149 Update LAB_JeffSinsel.md
b239f80 Complete lab report minus git logs
56d3062 yo @trevordbunch
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
(END)
Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)
[Branch] (https://drive.google.com/drive/u/1/my-drive)
### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.