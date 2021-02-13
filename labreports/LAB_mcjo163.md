# Lab Report: Requirements

___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Micah Johnson  
**GitHub Handle:** mcjo163  
**Repository:** [mcjo163/cis411_lab0_req](https://github.com/mcjo/cis411_lab0_req)  
___

## 1. Overview

The proposed system will allow students and faculty to order meals from on campus providers (Union & Falcon) and have them be delivered to a classroom building. Users will log into the system with Messiah's SSO and associate a default payment method with their account. Then, users will be able to select a delivery time and building, and then be redirected to the proper ordering website.

Once the order is placed, the system will work with the preexisting food service servers to send the order to the workers at the appropriate time, and then group orders together based on delivery time and building. Each classroom building will have an order pickup zone. Student workers will be needed to then deliver order groups from the food service sites to the pickup sites, as well as to man the pickup sites.

![Use Case Diagram](/assets/use-case-mcjo.png)

## 2. Requirements

The system requirements are as follows:

- **Business**: The business objective that the system needs to satisfy.
  - B.1. The system must limit orders based on staff capacity. (Trevor)
  - B.2. The orders placed through this system must charge students more, to cover the cost of delivery workers. (Josiah)
- **User**: The actions that a user takes within the system.
  - U.1. Users must associate their accounts with a default payment method (i.e. Dining Dollars, Credit Card, etc.). (Trevor)
  - U.2. User must provide a building and delivery time upon ordering. (Noah)
- **Functional**: The functions that the system must perform.
  - F.1. The system must not allow users to select impossible order times. (Trevor, modified)
  - F.2. The system must account for the food providers' operation hours. (Union Cafe Manager)
  - F.3. The system must group orders based on delivery time and location to optimize order delivery. (Noah)
  - F.4. The system must handle payment online so that users do not need to manually pay for their food. (Hungry Kid)
- **Non-Functional**: The characteristics that the system must have.
  - N.1. The system must render all webpages within 10 seconds of user interaction. (Trevor)
  - N.2. The system must be able to handle the same amount of web traffic handled by the food service sites. (Hungry Kid)
- **System**: Specifications about how the system must be built.
  - S.1. The system must use Messiah's SSO for handling accounts with the messiah.edu domain. (Trevor)
  - S.2. The system must be able to be turned on/off by administration when needed. (Josiah)
  - S.3. The system must redirect users to the chosen food provider's order website and must interact with their servers to avoid complications for workers. (Union Cafe Manager)

## 3. Assumptions

In order for this project to work, it is assumed that permission is granted to work with the existing food provider sites, so that the delivery orders can be sent through their systems seamlessly. Additionally, while the original business problem stated that orders would be delivered to the classrooms, it is believed that this would lead to disruptions, and so instead there will be a pickup area in each classroom building, and students can select a delivery time that would not coincide with their classes.

The proposed system would only be one part of making this idea work. It is assumed that the scope of this project is only focused on the system itself, and not as much the remaining infrastructure that would need to be established to make it work fully (hiring workers, setting up pickup locations, etc.). The requirements are written from the perspective of and limited to the scope of the system itself.

## Appendix: GitHub Notes

### A.1 Forked Repository

![fork diagram](/assets/git-diagram-mcjo.png)

### A.2 Git Logs

```powershell
787465c (HEAD -> labreport, origin/labreport) copied lan template @trevordbunch
3080719 (origin/main, origin/HEAD, main) typo in readme
33efb41 (upstream/main) formatted template
fd13d03 initial draft
ad87871 Create License
```

### A.3 Branch Repository

![branch diagram](/assets/branch-diagram-mcjo.png)

### A.4 Extra Credit

In this section, provide the round-trip diagram described in *Step 8*.
