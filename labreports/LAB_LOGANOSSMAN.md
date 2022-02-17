# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Logan Ossman  
**GitHub Handle:** loganossman  
**Repository:** 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  
___

## 1. Overview

![Use Case Diagram](/assets/Requirements.png)  

The above works with an assumed FIFO ticket system and electronic payment. Tip is given in the app, so no paper money is necessary. As the delivery system is connected with the tickets, the chef and deliverer will keep the customer up-to-date on the meal's progress. It is implied that the customer will order online, and they are the one ordering the food.

## 2. Requirements

    B1: The system must limit orders based on available staff. (Strict Manager)
    B2: Delivery service will adhere to Messiah's 30 minute rule, or else the food will be refunded. (Strict Manager)
    B3: The system will integrate the legacy system to save money. (Strict Manager)
    
    U1: Orders and progress must be accessible through their account. (Hungry Patron)
    U2: Cue of orders must be available for staff-side tracking. (In-house Chef)
    U3: Orders should be eliminated once fulfilled. (In-house Chef)

    F1: The system will display a progress bar which will be updated at each stage of the process. (PHungry Patron)
    F2: The system should print separate kinds of tickets whether they are in-house, pickup, or delivery. (In-house Chef)
    F3: Regular orders are kept track of in the app, and are connected to the person's account. (Hungry Patron)

    N1: The location of the delivery must be accessible by the deliverer. (Delivery Girl)
    N2: App load-time, actions, and user events should be less than 10 seconds. (Delivery Girl)
    N3: Visuals and font should be large for quick reference during work on staff-side. (In-house Chef)

    S1: Certain meals are only available during certain times of the day. (Strict Manager)
    S2: Meals cannot be ordered to Larsen 237, as only designated food items are allowed within. (Policy 8)
    S3: Meals must be to set locations like buildings and rooms, not outdoor spaces. (Strict Manager)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.

1. Online account are used to make purchases, and will not print order if low balance.

2. Deliveries are made on-campus only.


## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repository](/assets/Git_Branch_v_Fork.png)  

### A.2 Git Logs

    4076e81 (HEAD -> main, labreport) An image commit.
    5875e9a (origin/labreport) This is my last commit for @trevordbunch
    6badd56 your commit and reference @trevordbunch in the message
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
2.7


    6badd56 (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
    50d40f8 (origin/main, origin/HEAD, main) Update references to main branch
    ef962b1 Fix links in resource area
    237b52e Update Instructions for template file
    dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
    6293806 Merge pull request #1 from mcjo163/main
    7482f04 Typo in lab instructions
    3080719 typo in readme
    33efb41 formatted template
    fd13d03 initial draft
    ad87871 Create License
    Logans-MacBook-Air:cis411_
6.4

### A.3 Branch Repository

![Branch Repository Representation](/assets/Git_Feature_Branch_Creation.png)