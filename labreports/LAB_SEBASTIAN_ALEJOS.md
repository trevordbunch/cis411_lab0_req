# Lab Report: Requirements

___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Sebastian Alejos Acosta
**GitHub Handle:** [Sebastian Alejos](https://github.com/SebastianAlejos)  
**Repository:** <https://github.com/SebastianAlejos/cis411_lab0_req>
___

## 1. Overview

The problem posed is that the client would like to order a meal from an on-campus provider and have it delivered to his classroom.

### Use case diagram

![Use Case Diagram](/assets/use-case.jpg)
In this problem we have several actors that each have different actions and interactions with other actors.

**Customer**

- Orders the food.
- Pays for the food.
- Confirms his location to the delivery employee.
- He receives the food.

**Cashier**

- He confirms payment to the kitchen so they can start preparing food.

**Kitchen**

- Receives the order.
- Cooks the food.
- Hands food over for delivery.

**Delivery Employee**

-Delivers food.

## 2. Requirements

**Customer**

- I need to be able to place an order through the app.
- I need to be able to pay through the app
- I need to be able to give my location to get food delivered.

**Cashier**

- I need to confirm the payment of the customer.
- I need to let kitchen know that the payment was processed, so they can start cooking.

**Delivery Employee**

- I need to be able to see the location of the customer.
- I need to be able to confirm delivery. 

## Appendix: GitHub Notes

### A.1 Forked Repository

I
![Fork Diagram](/assets/fork.jpg)

### A.2 Git Logs

In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

```{
0a07b91 (HEAD -> labreport, origin/labreport) This is my first commit.  @trevordbunch in the message
8c0f29f (origin/main, origin/HEAD, main) Revert changes made during test
1fb6b7a Check if changes push
50d40f8 (upstream/main) Update references to main branch
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

In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)
![Branch Diagram](/assets/branch.png)  
Credit: By Akar, <https://medium.com/@aakarr.me/how-to-create-branch-in-git-6118de02a7c6>
