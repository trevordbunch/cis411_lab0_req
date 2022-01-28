# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Garrett Nissley  
**GitHub Handle:** ggn10  
**Repository:** [ggn10/cis411  ](https://github.com/ggn10/cis411_lab0_req) 
___

## 1. Overview
**Business Need**: 
“I would like to order a meal from an on-campus provider, and have it delivered to my classroom.”

**Information Gathered From Interviews**:
- **Union/Falcon Cafe Manager Interview**:
   - Orders must be picked up within 30 minutes are they are charged and cancelled.
   - There will only be some types of foods available for delivery order.
   - 3 delivery employees on per shift.
     -  They are provided a bike to assist in delivery times.
   - Orders will have to be limited to sustain 3 employees and 30 min. time frame.
- **Student Interview**:
   - Student expressed desire for system to provide an estimated time of delivery.
   - Delivery system will open new employment opportunities for students on campus.
- **IT Interview**:
   - Delivery system will integrate directly with the systems that are currently in place for the Falcon and Union cafes.
     - This is the smoothest way to create this system due to the quality of the system already in place for ordering food.
     - Additional option for 'delivery' will be added after the user selects the 'to-go' option when ordering food.
   - A campus map will be required for students to designate their delivery location.
   - Notification system will be accomplished through user's @messiah.edu email.
   - Delivery system is only possible through MU's SSO solution for accounts with messiah.edu domain.

**Overview of Business Process**:

![Business Process Diagram](/assets/BusinessProcess.png)

**Actors and Corresponding Tasks**:
1. **User**: This includes anyone who would order food for delivery. i.e. Student, Employee, Teacher
   - Confirm Messiah login for payment purposes
   - Place order
   - Designate delivery location
   - Be present to recieve food
2. **Cook**: Employee responsible for processing food orders and making the food
   - Confirm order
   - Cook food
   - Place food in designated "ready for delivery" area
3. **Delivery Employee**: Employee responsible for handling delivery process
   - Pick up order and notify user that delivery process has begun
   - Deliver food and verify user has recieved food
4. **System**: System responsible for processing delivery orders
   - Process order details (user account, food, delivery location)
   - Process payment according to messiah.edu account of user

**Outcomes**:
1. Messiah University will not have a food delivery system.
2. Messiah University will have a food delivery system that fails to fulfill the full scope of the business need.
3. Messiah University will have a fully-functioning food delivery system.
4. Messiah University will have a fully-functioning food delivery system that increases customer satisfaction.

## 2. Requirements
- **Business**: The business objective that the system needs to satisfy
  - B.1 The system must limit orders according to time frame (30 min). (Manager)
  - B.2 The system must limit ordering according to status of delivery employees. (Manager)
  - B.3 The system must be profitable for Messiah University.
  - B.4 The system must produce orders to fulfill delivery estimate time.
- **User**: The actions that a user takes within the system
  - U.1 The user must sign in using messiah.edu domain email.
  - U.2 The user must provide payment information.
    - U.2.1 The user must provide falcon dollars or meal plan.
    - U.2.2 The user must provide proper credit card information.
  - U.3 The user must select the proper food based on the menu for that day. (Manager)
  - U.4 The user must provide their location for delivery. (Student)
- **Functional**: The functions that the system should perform
  - F.1 The system must allow the user to login using messiah.edu account.
  - F.2 The system must provide the proper delivery menu. (Manager)
  - F.3 The system must process payment information and charge the user properly for their food.
  - F.4 The system must provide user with up-to-date campus map for location designation.
  - F.5 The system must provide user with estimated delivery time through messiah.edu email.
  - F.6 The system must allow user to confirm their order.
- **Non-Functional**: The characteristics that the system should have
  - N.1 The system must render pages in less than 15 seconds after user action.
  - N.2 The system must display food in a manner that allows for easy user selection.
  - N.3 The system should be able to handle 30 users without affecting performance.
  - N.4 The system must provide a campus map that allows for detailed location selection.
- **System**: Specifications about how the system should be built
  - S.1 The system will be built to integrate directly with the system that is already in place for Union Cafe and Falcon Cafe. (IT interview)
    - S.1.1 The system will use the SSO solution already in place for messiah.edu domain accounts.
    - S.1.2 The system will be built directly after the 'to-go' option of the current online ordering system.
  - S.2 The system will be built through HTML, CSS, and JavaScript.
  - S.3 The system campus map will be built through google maps.

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repo Diagram](/assets/ForkedRepositoryDiagram.png)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

```
2.7 Logs
{
    fd143ec (HEAD -> labreport, origin/labreport) Forked repo diagram
    bbf2193 Forked repo diagram
    fca42b4 Adding diagram to assests
    67a7f5f Modified fork diagram
    f35aba0 Added Forked Repo Diagram
    2b4330c Small changes
    ea506e4 Added template and started working on part 1
    55b9246 Committing my markdown lab file @trevordbunch
}
```

```
6.4 Logs
{

}
```

### A.3 Branch Repository
![Forked Repo Diagram](/assets/BranchDiagram.png)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.