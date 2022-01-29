# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2022  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Adam Lenker  
**GitHub Handle:** al1412  
**Repository:** https://github.com/al1412/cis411_lab0_req  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.    

The main problem is that users want to have food delivered to them in class rather than have to leave class or wait until class is over to get their food by walking over to the on-campus dining options where they ordered the food from. For this problem, a solution would be to design an application in which users can order their food without having to be physically present to pick up their orders when they are done. The user would need to first login through the college's login system to verify their status as a student or faculty member of the college, then select which of the on-campus dining options they would like to order from. In this way, the options are available through one website, instead of having to go to a different website for each dining option and log into those sites just to order. Additionally, the app must have webpages that are easy to navigate, so that way a user can easily adjust or cancel their order if needed, and it can give the user an exact time on when their food will be ready for delivery to their respective location. That way, there is no need for the user to have to miss class or important meetings to get their food as it will be brought to them instead. The desired outcome for this scenario is that the user successfully obtains their food at the location which they specify.    


## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.    
**Business:**    
B.1 The system must deliver food in a fast and effective matter. (LeeAnn Boyer)    

B.2 The system must base orders around what is currently avaiable for each dining option, indicating whether or not a certain item is available should such an event occur. (Brendan Hauer)    


**User:**    
U.1 The system must lead to a screen for the student to select if they want food from either the Falcon or the Union immediately after login. (LeeAnn Boyer)    

U.2 The system must lead the user to a screen where they can order their food after selecting the dining option they want food from. (LeeAnn Boyer)    

U.3 The system must associate the user with what building, floor, and room they are in. (LeeAnn Boyer)    

U.4 The system must display confirmation screen with the estimated time of food arrival and a button to press to let the eating place know when the student has gotten their food. (LeeAnn Boyer)    

U.5 If a dining plan other than the default one (Dining Dollars) is being used, the system must provide options for that sitaution so the user can select which payment plan they will use to pay for their order. (Brendan Hauer)    


**Functional:**    
F.1 The system must allow the student full access to both take-out eating options on campus. (LeeAnn Boyer)    

F.2 The system must offer fast and efficient delivery of meals wherever the student may be and must be able to reach wherever the student is on campus (the food
should arrive hot if it’s hot food and cold if it’s cold food). (LeeAnn Boyer)    

F.3 The system must indicate the approximate time which a user's food will be ready. (Brendan Hauer)     

F.4 The system must calculate the total cost of their order based on the prices of each option they selected, as well as how many of each option they selected. (Brendan Hauer)    


**Non-Functional:**    
N.1 The system must have user interfaces which are easy to navigate for each screen. (LeeAnn Boyer)     

N.2 The system must have full access to the menus of the eating place that the student chooses. (LeeAnn Boyer)    

N.3 The system must render pages without experiencing glitches or technical errors. (Brendan Hauer)    

N.4 The system must load pages within 3 seconds (at maximum) after a user clicks on an option from the previous page. (Brendan Hauer)    


**System:**    
S.1 The system must authenticate each user through the Messiah SSO (Single Sign-On) system to verify that users are Messiah students or faculty. (LeeAnn Boyer)     

S.2 The system must have the ability to go to a past window if a student changes their mind on what they want to order. (LeeAnn Boyer)    

S.3 The system must have the option to cancel the order if a student changes their mind. (LeeAnn Boyer)    

S.4 The system must automatically log out the user after ten minutes of inactivity (Brendan Hauer)    


## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  
![Repository diagram](https://user-images.githubusercontent.com/97567307/151079618-760d14d1-9e46-43be-b71c-2345e785d7fd.jpg)


### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

***Step 2.7 Git Log***    
`5816eee (HEAD -> main, origin/main, origin/HEAD) Merge branch 'main' of https://github.com/al1412/cis411_lab0_req`     
`c5e7e27 Lab report is located here @trevordbunch`   
`bf0f87a your commit and reference @trevordbunch in the message`   
`50d40f8 (upstream/main, origin/labreport, labreport) Update references to main branch`   
`ef962b1 Fix links in resource area`   
`237b52e Update Instructions for template file`   
`dafaf5e Merge pull request #2 from NedacNostrebor/patch-1`   
`6293806 Merge pull request #1 from mcjo163/main`   
`7482f04 Typo in lab instructions`   
`3080719 typo in readme`   
`33efb41 formatted template`   
`fd13d03 initial draft`  
`ad87871 Create License`    


***Step 6.4 Git Log***    
`8164428 (HEAD -> main, origin/labreport, labreport) Section 1 started`    
`8335824 Update LAB_al1412.md`    
`d1f0857 Added more requirements`    
`b8d840b More requirements added`    
`dbdb68a More requirements added`    
`9857dca Started requirements`    
`08628c2 Update LAB_al1412.md`    
`afebeca Syntax fixed`    
`e796926 Fixed syntax`    
`6397892 Update LAB_al1412.md`
`1da676f Update LAB_al1412.md`
`4f18e18 Update LAB_al1412.md`
`ae2b0cb (origin/main, origin/HEAD) Added diagram`    
`e86a120 Formatting errors fixed`    
`36a5118 Added Git log for step 2.7`    
`58144f6 Update LAB_al1412.md`    
`31b90a8 Update LAB_al1412.md`    
`22497ee Small update at top`    
`5816eee Merge branch 'main' of https://github.com/al1412/cis411_lab0_req`    
`c5e7e27 Lab report is located here @trevordbunch`    
`bf0f87a your commit and reference @trevordbunch in the message`    
`50d40f8 (upstream/main) Update references to main branch`    
`ef962b1 Fix links in resource area`    


Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)    
![Branch Repository diagram](https://user-images.githubusercontent.com/97567307/151678657-8d6a4aee-4593-41db-9789-e04537fd6e35.jpg)


### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.
