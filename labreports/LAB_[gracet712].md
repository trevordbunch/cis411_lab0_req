# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2023 
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Grace Taylor  
**GitHub Handle:** gracet712  
**Repository:** https://github.com/gracet712/cis411_lab0_req
___

## 1. Overview
 
![Business Process Diagram](/assets/business_process_diagram.jpg)  


Business problem: Create a system fulfilling the need to order a meal from an on-campus provider for delivery to a classroom.

Actors are:
1. Requesting individual.
2. Catering worker(s).

Tasks are:
1. Requester views menu info.
2. Requester places order.
3. Requester submits payment.
4. Payment is accepted or denied.
5. Catering worker(s) receive order and payment status.
6. Catering worker(s) add/update menu info.

Information:
1. Order data provided by requester (more detail below).
2. Data input by catering stipulating menu options, prices, available services, etc.

Outcomes:
1. The requester is able to place and pay for an order.
2. The catering worker(s) can view orders.
3. The system accepts only those orders that catering can fulfill and transmits them in a timely manner.

## 2. Requirements

- **Business**:
  - B.1 The system must specify whether an order's payment has successfully cleared so that catering will not fulfill an order that is unpaid for. (Catering Boss)
  - B.2 The system must require orders to be input at least 3 days in advance of the delivery date so that catering will be prepared. (Hope Tressler)
  - B.3 The system must include a setting for Messiah University holidays when no catering orders will be accepted or processed. (Catering Boss)

- **User**:
  - U.1 The user (requester) must be able to view and select menu items. (Dr. Weaver)
  - U.2 The user (catering worker) must be able to add, delete, and edit menu items. (Hope Tressler)
  - U.3 The user (requester) must be able to pay for the order via a Messiah University account or credit/debit card. (Hope Tressler)
  - U.4 The user (catering worker) must be able to view order details. (Catering Boss)

- **Functional**:
  - F.1 The system must render pages within 3 seconds. (IT Expert)
  - F.2 The system must encrypt payment data. (IT expert)
  - F.3 The system must make submitted orders available to catering workers within 1 minute of submission. (Catering Boss)

- **Non-Functional**:
  - N.1 The system must run on mobile devices and laptop and desktop computers. (Hope Tressler)
  - N.2 The system must be available at all times except for scheduled maintenance and holidays. (Catering Boss)
  - N.3 The system must support 75 concurrent users. (IT Expert)

- **System**:
  - S.1 The system must be compatible with Messiah University's EMS event planning system. (Hope Tressler)
  - S.2 The system must require Messiah University authentication. (Hope Tresler)
  - S.3 The system must employ a Web user interface for both requesters and catering workers. (Catering Boss)

## 3. Assumptions

Assumption 1: This system is intended to address the need of a faculty member or other mass event planner to order a meal for a classroom full of people (as opposed to an individual ordering a meal for themselves).

Assumption 2: This system deals only with order placing and processing, not meal preparation or delivery.

## Appendix: GitHub Notes

### A.1 Forked Repository
![Source Repository vs. Forked Repository](/assets/source_vs_fork_rep.jpg) 

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

Logs: Step 2.7
```

291cfa7 (HEAD -> labreport, origin/labreport) First commit for Lab 0 @trevordbunch
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

```

Logs: Step 6.4
```

1a49803 (HEAD -> main, origin/labreport, labreport) Sections A.2 and A.3 complete.
291cfa7 First commit for Lab 0 @trevordbunch
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

```

### A.3 Branch Repository
![Main Branch vs. Feature Branch](/assets/main_vs_feature_branch.jpg)

### A.4 Extra Credit
![Round Trip Diagram](/assets/round_trip_diagram.jpg)