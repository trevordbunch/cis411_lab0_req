# Lab Report: Continuous Integration
___
**Course:** CIS 411, Spring 2023 
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Ben Clarke  
**GitHub Handle:** BenOfTheOneRing
**Repository:** https://github.com/BenOfTheOneRing/cis411_lab0_req
___

# 1. Overview
Business problem:
“I would like to order a meal from an on-campus provider, 
and have it delivered to my classroom.”

To fix this problem we will create a web based application that allows a user to order food and have it delivered. 

The user will access the website via a web browser and then input their order, location, and payment. The website will then give a confirmation of the delivery and an estimated time of delivery. 

The website will tell the cooks who will make the order. The order will then be given to the runner who will be given the location order. The order will be handed to a runner who will bring it to the user's location. 

The user will provide the confirmation ID to verify their identity. 

Use Case Diagram:![Use Case Diagram](/assets/Lab0drawing3.svg)  

# 2. Requirements 

## Business
b.1: The system must limit orders based on staff capacity (ceo)

b.2: The system must be capable of accepting both falcon dollars and credit card info (a real anonymous user)

b.3: The system, including extra staff requirements, cannot increase the price of an order more than $1.50 (a real anonymous user) 

## User
u.1: User must be able input their current location, including building, floor, and classroom (a second real anonymous user) 

u.2: User must be able to input payment credentials (ceo)

u.3: User must be able to input and then change or cancel their order before submission (user compliance manager)


## Functional
f.1: The system must be able to send the users order confirmation ID (user compliance manager)

f.2: The system must be capable of receiving the required user input (user compliance manager)

f.3: The system must be able to calculate an estimated time of delivery (ceo)


## Non-functional
n.1: The system must securely transmit payment info (real cybersecurity major)

n.2: The system must have an intuitive and user friendly layout (user compliance manager)

n.3: The system must be able to render any page within half a second (web designer manager)


## System 
s.1: The system must be web based (head of marketing)

s.2: The system must be able to handle large amount of traffic (ceo)

s.3: The system must be able to produce unique confirmation ID tickets for each order (real cybersecurity major)

s.4: The system must be able to communicate to the on campus provider's cooks and runners (ceo)

s.5: The system must utilize mfa (real cybersecurity major)

# Appendix

a.1: Use Case Diagram:![Use Case Diagram](/assets/Lab0drawing1.svg)  


a.2:

    2.7 
    a4ce2e1 (HEAD -> labreport, origin/labreport) my commit @trevordbunch
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

    6.4 



a.3: Use Case Diagram:![Use Case Diagram](/assets/Lab0drawing2.svg)  