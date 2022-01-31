# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Kylie Firestone  
**GitHub Handle:** https://github.com/kfirestone25  
**Repository:** https://github.com/kfirestone25/cis411_lab0_req
___

## 1. Overview
Personnel of Messiah University would like the ability to order a meal from an on-campus provider and have it delivered to the classroom. After interviewing multiple members of the Messiah community (students, professors, food services managers, and IT specialists), it is quite evident that quality, speed, and system security are most important factors needed in the new system. 

![Use Case Diagram](https://docs.google.com/drawings/d/e/2PACX-1vRH2C9QfFWVmjZfjnGxw0zQQ-0O7-Qh22RRhy8rVGmNe2YNp6Us5GfFRTMiyHPd2x5lb9hKzu0fQmuJ/pub?w=753&h=528)


## 2. Requirements
#### Business
* B.1 System must check inventory, denying the user their order if proper ingredients are not readily available. (The Falcon Head Manager)
* B.2 System must ensure proper staffing capacity, limiting orders if delivery promise of 15 minutes cannot be accomplished. (Larsen Student Union Kitchen Manager)
#### User
* U.1 User must provide Messiah University credentials in order to access ordering service. (Kenzie Spodnik)
* U.2 User must link payment type to fulfill order (Dining Dollars, Falcon Dollars, credit/debit card). (Michael Zigarelli)
#### Functional
* F.1 System must provide the user with an estimated delivery time before order is confirmed. (Lindsay Haseltine)
* F.2 System must send a confirmation email of the order to the user's email within the messiah.edu domain. (Rodney Sauder)
#### Non-Functional
* N.1 System must load page within 5 seconds of user interaction. (Thomas from IT)
* N.2 To ensure enhanced security of user information, password will not be displayed opon entering into the system. (Kathleen from IT) 
#### System
* S.1 Before allowing an order placement, the system must verify that the user is affiliated with the messiah.edu domain by prompting the user to enter their username and password. (Policy 102)


## Appendix: GitHub Notes

### A.1 Forked Repository
Below is a diagram that demonstrates the relationship between the source repository and my forked repository:   

![Relationship Diagram](https://docs.google.com/drawings/d/e/2PACX-1vQrbI1HATWy00xdbU4zgkhMK2Ua2HaqndN3wZ_pKC8R8KcnmWsrQL06XBCmwqgp2qYvJCYy1E-xbgOo/pub?w=962&h=363)

### A.2 Git Logs

#### Step 2.7 Log

```
kylie@DESKTOP-PR6DBD9 MINGW64 /c/GitHub/cis411_lab0_req (labreport)
$ git log --oneline
c0e429e (HEAD -> labreport, origin/labreport) my first commit @Cmcculler
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
```
#### Step 6.4 Log

```

```

### A.3 Branch Repository

Below is a diagram that demonstrates the relationship between my main branch and my feature branch in my repository:

![Relationship Diagram](https://docs.google.com/drawings/d/e/2PACX-1vThYlPOzzc5DQWzKZcasvGbVi246zNroia0g75u92FovIYeALk20NTIrgUFRBqodzApcCfHA5YLEldG/pub?w=716&h=271)

