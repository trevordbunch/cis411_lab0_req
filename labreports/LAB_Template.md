# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Nathan Bowman 
**GitHub Handle:** Bowman3239 
**Repository:** https://github.com/bowman3239/cis411_lab0_req  
___
## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

https://github.com/bowman3239/cis411_lab0_req/blob/git-checkout--b-labreport/CIS411Lab00FoodDrawing.jpg

This picture shows how a student can order food on campus and have it deliverered to their room. 
The chef will always have food prepared, so as the client orders and pays, the food will be given to another work to deliver the food to the client.

## 2. Requirements
Business - The business objective that the system needs to satisfy:
  B1. - The system only runs when the kitchen is open. (Student 1)
  B2. - The system only shows food that is available at that given moment. (Student 2)
 
User - The actions that a user takes within the system.
        U1. - The user must attend Messiah University and be connected to Messiah Wifi. (Student 2).
        U2. - The user must select what type of payment option they will be paying with. (TBunch)
 
Functional  - The functions the system should perform.
        F1. - The system must present an anticipated delivery time prior to allowing the user to confirm the order. (TBunch)
        F2. - The system must incorperate all toppings and customizable options that are permitted within kitchen guidelines. (Student 2)
        F3. - The system shall incoperate pictures of the food that is being offered. (Student 2).
  
Non-Functional - The characteristics that the system should have
        N1. - The system must render pages in less than 10 seconds after any user action or application event. (TBunch)
        N2. - The system will have a live feed of the kitchen so students can watch their food be prepared. (Student 1)
        
Systems - The specification about how the system should be built.
        S1. - The system must use Messiah University Signle Sing On (SSO) solution for any accounts with a messiah.edu domain (TBunch)
        S2. - The system will always be live, but while the kitchen is closed, will show a message saying "We are not taking any orders at this time. Sorry for the inconvenience." (Student 1) 

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes


### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

[[https://github.com/bowman3239/cis411_lab0_req/blob/git-checkout--b-labreport/CIS411Lab00FoodDrawing.jpg?raw=true]]

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.
