# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Ammanuel Tamrat  
**GitHub Handle:** AmmanuelT  
**Repository:** Your Forked Repository  
___

## 1. Overview
There are three actors. The user, the dinning service staff and the delivery person. The user must first go onto the system and order the food. The dinning service staff will receive the order and will prepare the food. The delivery person must then take the food and deliver it to the user. Once the food arrives to the user the delivery person will confirm having delivered the food and the user must also confirm receiving the food. The user must then pay and the dinning service staff will accept the payment.
 
![Use Case Diagram](/assets/useCase.svg)  


## 2. Requirements
- Buisness Requirements:
    - B.1 The system must limit the orders based on the availability of ingredients, so that the ordered food can be preparred.(Young Dining Service Manager)
    - B.2 The system will require confirmation on delivery from both the driver and the user, to make sure that the food has properly been delivered.(Concerned Union Boss)
    - B.3 The system must allow dinning services to modify available food options, so that seasonal foods can be added or removed.(Dining Service Manager)
- User requirements:
    - U.1 The user must povide a valid messiah email adress. (Cyber Security Student)
    - U.2 The user must provide an on campus location. (Kelly Apartment Student)
- Functional Requirements:
    - F.1 The System will allow users to add or remove ingredients from food( Student)
    - F.2 The System will offer the live location of the food being delivered(Hungry Student)
- Non-Functional Requirements:
    - NF.1 The System will ask for confirmation twice so that the user doesn't order food by accident.(Concerned Staff Member)
    - NF.2 The System must provide nutritional information for the available food options.(Nutrition Student 1)
    - NF.3 The System will have brightly colored allergens warnings for the available food options. (Nutrition Student 2)
- System Requirements:
    - S.1 The system must only allow users to sign in when connected to Messiah Secure wireless network.(IT department staff 1)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
[diagram of forked repository](/assets/forkedRepo.svg)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
[diagram of forked repository](/assets/labereportBranch.svg)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.