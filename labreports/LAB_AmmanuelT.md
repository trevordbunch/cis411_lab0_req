# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Ammanuel Tamrat  
**GitHub Handle:** AmmanuelT  
**Repository:** [Forked Repository](https://github.com/AmmanuelT/cis411_lab0_req.git)
___

## 1. Overview
There are three actors. The user, the dinning service staff and the delivery person. The user must first log onto the system using their messiah email. The user will then enter their location on campus and pick food from the provided menu. The user will then confirm their order and will receive the live location of the food. The dinning service staff will receive the order and will prepare the food. The delivery person must then take the food and deliver it to the user. Once the food arrives to the user the delivery person will confirm having delivered the food and the user must also confirm receiving the food. The user must then pay and the dinning service staff will accept the payment.

![Use Case Diagram](/assets/use.svg)  

## 2. Requirements
- Buisness Requirements:
    - B.1 The system must limit the orders based on the availability of ingredients, so that the ordered food can be preparred.(Young Dining Service Manager)
    - B.2 The system will require confirmation on delivery from both the driver and the user, to make sure that the food has properly been delivered.(Concerned Union Boss)
    - B.3 The system must allow dinning services to modify available food options, so that seasonal foods can be added or removed.(Dining Service Manager)
- User requirements:
    - U.1 The user must povide a valid messiah email adress. (Cyber Security Student)
    - U.2 The user must provide an on campus location. (Kelly Apartment Student)
- Functional Requirements:
    - F.1 The System will allow users to add or remove ingredients from food(Exercise Science Student)
    - F.2 The System will offer the live location of the food being delivered(Hungry Student)
- Non-Functional Requirements:
    - NF.1 The System will ask for confirmation twice so that the user doesn't order food by accident.(Concerned Faculty Member)
    - NF.2 The System must provide nutritional information for the available food options.(Nutrition Student 1)
    - NF.3 The System will have brightly colored allergens warnings for the available food options. (Nutrition Student 2)
- System Requirements:
    - S.1 The system must only allow users to sign in when connected to Messiah Secure wireless network.(IT department staff 1)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
![diagram of forked repository](/assets/forkedRepo.svg)

### A.2 Git Logs
logs from *Step 2.7*

```
→ a0c9ca7 (HEAD -> labreport, origin/labreport) added use case diagram
bash: syntax error near unexpected token `HEAD'
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
```

logs from *Step 6.4*

```
f44e450 (HEAD -> main, labreport) fixed links
d026606 (origin/labreport) added diagram for step 8 & fixed overview
117448c added diagram for step 8 & fixed overview
a39879a fixed diagrams
68f58a7 fixed diagrams
590d185 fixed diagrams
f0ed4a3 fixed diagrams
530b969 fixed diagrams
d66a8a0 fixed diagrams
4f9e646 fixed diagrams
547f848 added more diagrams and Buisness Problem
6176cd1 added more diagrams and Buisness Problem
a0c9ca7 added use case diagram
500d5cb added requirements
383850c first lab report commit @trovordbunch
50d40f8 (origin/main, origin/HEAD) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
```

### A.3 Branch Repository
![diagram of labreport branch](/assets/labreport.svg)

### A.4 Extra Credit
 ![diagram of round-trip of code](/assets/roundtrip.svg)