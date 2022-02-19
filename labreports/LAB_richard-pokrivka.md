# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Richard Pokrivka  
**GitHub Handle:** richard-pokrivka  
**Repository:** https://github.com/richard-pokrivka/cis411_lab0_req  
___

## 1. Brief Overview of the Business Problem


![Use Case](https://docs.google.com/drawings/d/e/2PACX-1vQ3LX-ntncsVKXqaj7ZQp6_v5FyNy4OlMff-_D74jFk918veTlx7LbVW44H-6lP70fWWRXXNuB2wJdE/pub?w=1323&h=721)  
Credit: By Richard Pokrivka and Corum McCuller, https://docs.google.com/drawings/d/e/2PACX-1vQ3LX-ntncsVKXqaj7ZQp6_v5FyNy4OlMff-_D74jFk918veTlx7LbVW44H-6lP70fWWRXXNuB2wJdE/pub?w=1323&h=721


This image describes the business process for creating a process for Messiah food to be delivered to Messiah Clients through an application. The person ordering the food would first authenticate being a Messiah Member. Then they would choose the food and or drink and confirm the method of payment and delivery location. Once the order is placed the chef accepts the order and prepares it and the delivery worker accepts the order delivery. Once the food is prepared, the delivery worker picks it up and gives it to the client.

## 2. Requirements

### Business: 
--There will be a cap on the amount of food being ordered to limit the kitchen staff from being overwhelmed and prevent a safety hazard for the delivery staff. (Head of Messiah Dining Services)

--The system must limit or deny orders based on time and amount ordered. This prevents problems when large orders would be placed close to closing time when the kitchen is cleaned and ready to be shut down. (Head of the Union)

### User: 
--The user must have the option to use an alternate form of payment method and can save that information to the individual user. (e.g., Falcon Dollars or Credit Card) (Ryan Fascetta, Messiah Student).

--The user can save food orders and delivery locations to an account to make ordering next time easier (Lazy Student)

### Functional: 
--The system must provide a confirmation message to the user placing the order and sends a message saying not being at the presumed location for pickup warrants missing out on the order. (Head of IT).

--The system must present an anticipated delivery time prior to order confirmation and offer order cancellation if the wait is seemingly too long. (Owen Joyce, Student)

--System must be able to accept credit card if user is not using Messiah meal plan (Rj Mellor, Messiah Student)

### Non-Functional: 
--Multiple different hyperlinks starting with different restaurants, and then different food options. (Software Developer)

--The system should display nutritional information about the food and general information of the different restaurants on campus so the purchaser, who may be new to Messiah, has a better understanding of what they are ordering. (Freshman Transfer Chad)
  
### System: 
--The system should utilize the Messiah authentication to ensure the purchaser is present on Messiah grounds and has ties to the institution. (P-Safety Officer)

--The system should limit the number of orders that can be placed by one account in a certain time period in case of scenarios where another person has access to an account and could spend all the money. This feature is similar to the vending machine limit. (Old Main financial worker)


## Appendix: GitHub Notes

### A.1 Forked Repository
![Use Case](https://docs.google.com/drawings/d/e/2PACX-1vS3pzCRX_pG8zsB68w0lvPSUaR7L6cbkeUzzEiLXoGy5rLrAhb0KzuH5On3mS4ZKkM2e9rJKnxTASXi/pub?w=1092&h=711) 

### A.2 Git Logs
~~~
Log from Step 2.7

9c8c222 (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
ee425cd (origin/main, origin/HEAD, main) Delete git checkout -b labreport
f2c818a Create git checkout -b labreport
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
~~~
~~~
Log from Step 6.4
074a606 (HEAD -> main) Merge branch 'labreport'
a3158df (labreport) your commit message @cmcculler1 yolo
1a3e344 (origin/main, origin/HEAD) Delete ProjectDiagram.jpg
97ec2e7 Add files via upload
9c8c222 your commit and reference @trevordbunch in the message
ee425cd Delete git checkout -b labreport
f2c818a Create git checkout -b labreport
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
~~~


### A.3 Branch Repository
![Use Case](https://docs.google.com/drawings/d/e/2PACX-1vTtY_I_fl5RGno1D-ajNwmo6R4v1Isr6lTCECPbG4sKb9v6thpKrWqerTGx5Pc6WAcEWGIlH1iJn4R8/pub?w=1401&h=730)
