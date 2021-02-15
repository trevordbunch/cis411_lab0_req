# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Josiah McCracken  
**GitHub Handle:** [Scribhneoir](https://github.com/scribhneoir)  
**Repository:** [source repository](https://github.com/scribhneoir/cis411_lab0_req)  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.
![Use Case Diagram](/assets/Use_case_restaurant_model.svg)  
Credit: By Josiah McCracken

## 2. Requirements

- **Business**
    - B1. The system must limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 minutes of promised delivery is not placed in jeopardy. (Treavor)
    - B2. Must be additional delivery cost(Mr. Bossman Jr.)
    - B3. 
- **User**
    - U1. User must provide room number and building upon order (Dogbert)
    - U2. The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Treavor)
- **Functional**
    - F1. The system must present an anticipated delivery time prior to allowing the user to confirm the order (Treavor)
    - F2. System must account for when establishments are open, and only allow for orders within this window (Micah)
    - F3. The system must present the additional delivery cost before finalizing the order (Dogbert)
- **Non-Functional**
    - N1. The system must render pages in less than 10 seconds after any user action or application event (Treavor)
    - N2. Handle same web traffic as union on superbowl sunday (Micah)
- **System**
    - S1. The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain (Treavor)
    - S2. Must be able to toggle on and off remote ordering and delivery through admin portal (Mr. Bossman Sr.)
    - S3. Built off of preexisting union and falcon web ordering pages, adding additional checkout method "delivery" (Dilbert)


## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes
### A.1 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your master/main branch and your feature branch in your repository (*Step 2.8*)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.