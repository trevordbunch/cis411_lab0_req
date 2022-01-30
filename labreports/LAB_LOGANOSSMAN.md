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

* Business
    * The system must limit orders based on available staff. (Harold the Manager)
    * Delivery service will adhere to Messiah's 30 minute rule (Nibel the Gourmet)
* User
    * Orders and progress must be accessible through their account. (Nibel the Gourmet)
* Functional
    * The system will display a progress bar which will be updated at each stage of the process. (Nibel the Glutton)
    * The system should print separate kinds of tickets whether they are in-house, pickup, or delivery. (Joey the Chef)
* Non-Functional
    * The location of the delivery must be accessible by the deliverer. (Jenny the Deliverer)
    * App load-time, actions, and user events should be less than 10 seconds. (Jenny the Deliverer) 
* System
    * The system will integrate the legacy system to save money. (Harold the Manager)

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