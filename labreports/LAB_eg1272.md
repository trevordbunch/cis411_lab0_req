# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Elias Gregory  
**GitHub Handle:** [eg1272](https://github.com/eg1272)  
**Repository:** https://github.com/eg1272/cis411_lab0_req  
___

## 1. Overview
Messiah University wants to have a system where an individual can order a meal from an on-campus provider and have it delivered to a classroom.

![Use Case Diagram](/assets/use-case.png)

A feature development shall be made so that an individual will be able to select a classroom location using the on-campus university ordering system. When an order is made using the classroom option, the client must make payment before the on-campus provider will accept/confirm the order. Once an order is confirmed, its details will be printed to the kitchen like any other order. The cooks will create the order, and set it on the delivery-bay with its attached instructions. Deliverers will read the location, bring it to the destination, and the client will have received their order. 

## 2. Requirements

Business - Create a system/feature that allows individuals on the University Campus to order food from the on-campus provider, to a classroom. (Must)
Source: 

User - The user will order food from the online order system, there will be an option for them to select a classroom location for delivery. This will change their order from the standard to new delivery option. (Must)
Source:  

Functional - Receive orders from those connected to the University Network. Have those orders be relayed to the relevant on-campus food provider. (Must)
Source:

Non-Functional - System shall be quick, robust, not prone to errors, and user-friendly. (Must) Requires a GUI usable on mobile devices, and be compatable Windows/MacOS operating systems. Also to be compatable with major browsers, specificly Chrome, Safari, Edge & Firefox. (Must)
Source:

System - Specifications about how the system should be built.
Source:

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 &3 Forked Repository
![ForkedRepo](/assets/forkedRepo.png)
This shows the relationship between all branches. The Master branch is pulled down to a student-forked master branch. The student then creates a sub-branch under their forked-master to start making local commits. After a series of commits they push to their own forked-master. In the end they send a pull-request to the true master branch so that owner can see all the changes.

### A.2 Git Logs