# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Noah Brenneis  
**GitHub Handle:** NoahBrenneis  
**Repository:** NoahBrenneis/cis411_lab0_req  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

Here is an example of including a image into your lab report using a URL:  
![Use Case](https://commons.wikimedia.org/wiki/File:Use_case_restaurant_model.svg#/media/File:Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

Here is an example of including a image into your lab report using an uploaded file:  
![Use Case Diagram](/assets/Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

![use case diagram](/assets/Food%20Delivery%20UCD.svg)

In this scenario, the customer, who is a student at a university, is able to order food from the campus's on-site food services and have it delivered to somewhere on campus.

Besides the web server needed to run the service, there are three types of people involved: the customer who orders the food, the cook who prepares it, and the delivery person who brings it to the customer. In addition, the customer's bank account is used as a means of payment.

The customer's primary action is to place an order, which has four steps: selecting the food items to purchase, indicating the on-campus delivery location, adding the needed payment info, and processing the order. The cook then receives the order and prepares it, at which point it is made ready for pickup by the delivery person. This delivery person will then deliver the order to the location specified by the order, at which point the customer receives it and the process is finished.

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

### Business Requirements
- B.1 - The system must only allow orders to be placed if there are a sufficient number of delivery workers capable of making deliveries (My Younger Brother)
- B.2 - The system must allow for refunds for situations where a placed order is cancelled (Frugal Student)
### User Requirements
- U.1 - The user must be able to store their payment information, allowing them to automatically enter it in future transactions (My Younger Brother)
- U.2 - The user must be able to enter a payment method, delivery time and location at checkout (My Sister)
### Functional Requirements
- F.1 - The system must allow for multiple different items to be ordered at once using a cart system (My Sister)
- F.2 - The system must send users an order confirmation message, either through a connected email or phone number (My Sister)
- F.3 - The system must allow for users to provide confirmation that their orders were properly delivered (My Sister)
- F.4 - The system must provide an order status to the user, displaying the progress of their order (My Younger Brother)
### Non-Functional Requirements
- N.1 - The menu used by the system must provide allergen information (My Sister)
- N.2 - The system must only be usable by students on the campus (Concerned Professor)
### System Requirements
- S.1 - The service must have a website with which the user can place orders and provide payment (My Younger Brother)
- S.2 - A server must be used to store the possible food items, track orders, and remember payment information (My Younger Brother)
- S.3 - The system must utilize the university's student account system to allow students to log in and place orders using them (My Sister)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

Users of this system are expected to use a personal computer or mobile device, and as such the system is expected to be able to run on commonly used devices.

Because universities are not open during certain periods of the year, the service is not expected to function during those periods.

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

![fork relationship diagram](/assets/Fork%20Relationship.svg)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

Log from Step 2.7:
``` json
$ git log --oneline
8a0c27c (HEAD -> labreports, origin/labreports) Added name, github handle and repo URL to the heading of the lab report.
3c46adc Made a copy of the lab template provided by @trevordbunch.
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

Log from Step 6.4:
``` json

```

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

![branch relationship diagram](/assets/Branch%20Relationship.svg)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.