# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Caden Robertson
**GitHub Handle:** NedacNostrebor 
**Repository:** [Forked Repository](https://github.com/NedacNostrebor/cis411_lab0_req)
___

## 1. Overview
The system will allow students to order food from one of the on campus resturaunts and have it delivered to them in class. The student will enter their order, payment method, and delivery location. The chef will cook the food and send it off to the delivery workers to deliver it to the specified location.

![Use Case Diagram](/assets/assets_NedacNostrebor/UseCase.svg)  

## 2. Requirements

- **Business**: The business objective that the system needs to satisfy.
  - B.1 The system must limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 minutes of promised delivery is not placed in jeopardy. (Pointy Hair Boss)
  - B.2 The system must aprove there is enough in the user's available balance before sending through the order.(John smith)
  - B.3 The system must track the progress of orders. (Isaac)
- **User**: The actions that a user takes within the system
  - U.1 The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Hungry Student 1).
  - U.2 The user must choose what food they would like to order from the available options.(Joe Smith
  - U.3 The user must choose what room they would like their food delivered to.(Isaac)
- **Functional**: The functions should the system perform
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Hangry Student 2).
  - F.2 The system must provide a space to add special requests to the order.(ex. Enter through the back door)(Isaac)
  - F.3 The system must have a way to contact management in case there is a problem with an order.(Mason)
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
  - N.2 The system must have a visually appealing interface.(Mason)
  - N.3  The system must be able to handle heavy traffic.(John Snow)
- **System**: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
  - S.2 The system must be able to be turned off during the off hours.(Mason)
  - S.3 The system must work on both mobile and desktop browsers(Tom Thumb)


## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository

![Forked Repository](/assets/assets_NedacNostrebor/ForkedRepository.svg)  

### A.2 Git Logs

```powershell
ac75bcf (HEAD -> labreport) Coppied lab report @trevordbunch
33efb41 (origin/main, origin/HEAD, main) formatted template
fd13d03 initial draft
ad87871 Create License
```

```powershell
1464169 (HEAD -> main, labreport) requirements
ac75bcf Coppied lab report @trevordbunch
33efb41 (origin/main, origin/HEAD) formatted template
fd13d03 initial draft
ad87871 Create License
```

### A.3 Branch Repository

![Branch Repository](/assets/assets_NedacNostrebor/BranchRepository.svg)  

### A.4 Extra Credit

![Round Trip](/assets/assets_NedacNostrebor/RoundTrip.svg)  