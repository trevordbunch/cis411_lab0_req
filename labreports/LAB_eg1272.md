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

Source: Kim S. Phipps, President "I want this order system to work for everyone on-campus. Students and Teachers should be able to use the current order system to send food to classrooms across campus"
-----------------------------------------------------------------------------------------------------------------------------------

User - The user will order food from the online order system, there will be an option for them to select a classroom location for delivery. This will change their order from the standard to new delivery option which the delivery-staff will be attached to. (Must)

Source: Kathie Shafer, VP for Operations "Basically, this new deilivery system will need to give instructions to the delivery staff. They will need a way to know where to go, so our users will need to select the classroom they want food delivered to in this system."  
-----------------------------------------------------------------------------------------------------------------------------------

Functional - Receive orders from those connected to the University Network. Have those orders be relayed to the relevant on-campus food provider. (Must)

Source: Brian Sheaffer, Network Admin "This system will need to take orders from our network and relay it to the correct place"
-----------------------------------------------------------------------------------------------------------------------------------

Non-Functional - System shall be quick, robust, not prone to errors, and user-friendly. (Must) Requires a GUI usable on mobile devices, and be compatable Windows/MacOS operating systems. Also to be compatable with major browsers, specificly Chrome, Safari, Edge & Firefox. (Must)

Source: Tony Wyland, Director Tech "Many of our students like to order on their phones, this system needs to work on mobile devices and different OSes, mainly MACos and Windows. We also use Edge on our Campus Computers. Make sure the system is compatable with the Top 4 major Browsers." 
-----------------------------------------------------------------------------------------------------------------------------------

System - Will require the use of the current Database SQL, major additions to the Order System/GUI, added ability of payment system to processes payments online. 

Source: David Walker, VP for Finance "With this new system students will have to pay up-front online before we send food out. I dont want the problem of un-claimed food on deliveries. Our current system does not have this ability."
-----------------------------------------------------------------------------------------------------------------------------------

## 3. Assumptions
Other features to consider include:
-Phone notification system that informs users when their order has begun processing/is being sent out. 
-Uber-like delivery-acceptance system so that there does not need to be a large group of on-staff delivery-people.
-Whitelist system so only certain people can order food to classrooms.

## Appendix: GitHub Notes

### A.1 &3 Forked Repository
![ForkedRepo](/assets/forkedRepo.png)
This shows the relationship between all branches. The Master branch is pulled down to a student-forked master branch. The student then creates a sub-branch under their forked-master to start making local commits. After a series of commits they push to their own forked-master. In the end they send a pull-request to the true master branch so that owner can see all the changes.

### A.2 Git Logs