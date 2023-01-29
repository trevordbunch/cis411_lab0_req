# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Nason Allen
**GitHub Handle:** 02NRA
**Repository:** https://github.com/02NRA/LAB_02NRA/branches
___

## 1. Overview
Our goal for this program is to create a service that delivers on-campus food sources directly to students in classes. In interviewing two students, Courtney and Peyton, we discovered that there would be great conveniance for students whose schedules would not allow them to eat certain meals throughout the day. There were also concerns raised about professors who find that the service distracts their students. Both these benefits and drawbacks will be addressed in the features offered by this service.[include chart]

Use Case Diagram 
![Use Case Diagram](/assets/Lab_Use_Case.jpg)  
Made using Google Drawing

## 2. Requirements
#Business
Meals will be delivered to the students from on-campus food suppliers, as per the given text
~~~
“I would like to order a meal from an on-campus provider, and have it delivered to my classroom.”
~~~
#User
A user will make an order online, after logging into their Messiah account, describing the desired meal (from a menu), and the delivery destination.
#Functional
The system will allow a cook to view an order placed by a customer (in this case, also a student). This order will then be visible to the person delivering the order, or in print.
#Non-Functional
The system should be streamlined, and as linear as possible, so that the user can easily navigate the different menus of the different sources of food. There should also be preexisting options for delivery locations, so there is not confusion over misinputs. 
#System
-The system will connect with students' existing Messiah accounts, so that they can use their dining dollars to make payment for the food.
-If the students' account has no dining dollarsavailable, the student can pay by other electronic means, such as PayPal.
-The system will connect to the ticket printer's native software to convey the data inputted by the user (whichever ticket printer is relevant to the order, be it Union, Falcon, Lottie, or Cafe Diem).
## 3. Assumptions

## Appendix: GitHub Notes

### A.1 Forked Repository
Lab Fork Diagram 
![Lab Fork Diagram](/assets/Lab_Fork.jpg)  
Made using Google Drawing
### A.2 Git Logs
~~~
Nason@Kritchs-Blade MINGW64 ~/Documents/GitHub/LAB_02NRA (labreport)
$ git log --oneline
b3865e8 (HEAD -> labreport, origin/labreport) Following initial instructions @trevordbunch
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD, main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License

Nason@Kritchs-Blade MINGW64 ~/Documents/GitHub/LAB_02NRA (labreport)
$ git log --oneline
b4dea3e (HEAD -> labreport, origin/labreport) First Edit @trevordbunch
b3865e8 Following initial instructions @trevordbunch
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD, main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License

Nason@Kritchs-Blade MINGW64 ~/Documents/GitHub/LAB_02NRA (labreport)
$ git log --oneline
eef31ac (HEAD -> labreport, origin/labreport) Final Edit @trevordbunch
b4dea3e First Edit @trevordbunch
b3865e8 Following initial instructions @trevordbunch
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD, main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License

Nason@Kritchs-Blade MINGW64 ~/Documents/GitHub/LAB_02NRA (main)
$ git log --oneline
52fad83 (HEAD -> main, labreport) Final
eef31ac (origin/labreport) Final Edit @trevordbunch
b4dea3e First Edit @trevordbunch
b3865e8 Following initial instructions @trevordbunch
50d40f8 (upstream/main, upstream/HEAD, origin/main, origin/HEAD) Update references to main branch
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
Main and Feature Branches Diagram 
![Main and Feature Branches Diagram](/assets/Branch_and_features.jpg)  
Made using Google Drawing
### A.4 Extra Credit
