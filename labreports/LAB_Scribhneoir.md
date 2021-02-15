# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Josiah McCracken  
**GitHub Handle:** [Scribhneoir](https://github.com/scribhneoir)  
**Repository:** [source repository](https://github.com/scribhneoir/cis411_lab0_req)  
___

## 1. Overview
The system provides an accurate menu to the user based off of the time, ready ingredients, and available staff. The user will then order food, provide payment, and request a delivery location. The system shall send the order to the chef to cook, the delivery location to the deliverer, and a time estimate to the client when the food will be delivered. The chef will make the food, and give it to the deliverer, who will then deliver it to the requested location and give it to the client within the allotted time frame.
![Use Case Diagram](/assets/usecase.svg)  
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


## Appendix: GitHub Notes
### A.1 Git Logs
3c4bd18 (HEAD -> main, labreport) Finished requirements and added diagrams
dafaf5e (origin/main) Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License

### A.2 Github diagram
![Github Diagram](/assets/github.svg)