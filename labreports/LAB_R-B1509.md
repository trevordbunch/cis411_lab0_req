# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Rachel Beattie
**GitHub Handle:** [Your GitHub Handle ](https://github.com/R-B1509) 
**Repository:** [Your Forked Repository](https://github.com/R-B1509/cis411_lab0_req)  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

Business Need: “I would like to order a meal from an on-campus provider, 
and have it delivered to my classroom."

#### **Actors**

  1. Client: Orders food, Pays for food 
  2. Deliverers: Deliver Food
  3. Chefs: Cooks Food 

#### **System Tasks**

 1. Ordering food from System
 2. Link account information, confirm location and give estimated delivery time
 3. Confirm Order by customer and system
 4. Order recorded in system
 5. Payment transaction confirmation
   1. Order information to chef
   2.  Payment information to a separate financial system
   3. Location details given to delivery person
 6. Delivery of food within estimation of time to specified location

#### **Info**
3.1 Backfeed of safety check of area hazards and possible allergans i.e. No food in a chemistry lab, art studios due to toxic paints, biology/nursing/health with autopsy due to sanitation,physics, basically any sort of lab, disruption<br>
5.2 Update information on provisions each time an Order is fufilled but before Delivery

#### **Outcomes**

1. Confirmation of transactions
2. Delivery of food
3. Financial updates to seperate system
4. Update information on supplies


[Simple Diagram](https://drive.google.com/file/d/1FeSquaX99_ltCL5PJ2VPnXg6ZAtJvSji/view?usp=sharing)

Here is an example of including a image into your lab report using a URL:  
![Use Case](https://commons.wikimedia.org/wiki/File:Use_case_restaurant_model.svg#/media/File:Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

Here is an example of including a image into your lab report using an uploaded file:  
![Use Case Diagram](/assets/Use_case_restaurant_model.svg)  
Credit: By Kishorekumar 62, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7880320

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

#### **Business**: Business Objective of system
   1. Deliver Food in estimated time
   2. Ensure safety of students and faculty

#### **User**: Client-side interaction
 1. User Account must be associated with payment method, i.e. Falcon Dollars, Credit Card (lessonsLearned.md File Example)

#### **Functional**: The functions the system should perform

   1. The system must present a precise delivery time prediction prior to allowing the user to confirm the order to help ensure that they will be at the location given ("Hangry Student 2" from lessonsLearned.md File Example, co-worker at Lotties).
   2. Resources must be updated after every confirmation of Order and Payment (Self)
   3. Check for constraints before final confirmation of Order on the System's side (Self)

#### **Non-Functional**: The characteristics that the system should have.
   1. The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady, lessonsLearned.md File Example)
   2. The system should update any changes in food stock on Business End (Self)
   3. Any food allergy items list ingredients in order form (Self, Faculty-Member)
   
 #### **System**: Specifications about the build
   1. The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
   2. There must be a prior agreement with the classroom's professor before the any order is confirmed that allows for food delivery (Faculty Member)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented. 
 
 #### **Constraints**
1. Prohibitation
   1. No food is allowed to be delivered to Hazard Zones, i.e. Science Labs, classes with Chemical Usage, Art Studios due to toxic paints (Co-worker)
   2. No food allowed in food labs for academic integrity (Faculty Member)
2. There must be a prior agreement that allows for food delivery with the classroom's professor before any confirmation message is sent to the student confirming their order (Faculty Member)
3. Allergies
   1. Double check the class attendance where food is delivered to for any extreme food allergy, as in, flare-up if allergen is just touched or nearby (Faculty Member)
   2. Food Allergens listed in Menu description of food (Self, from discussion with Faculty-Member)

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*

[Diagram](https://app.diagrams.net/#G1RKvuqzau33citIMrWbnYxsMjq2FHRlh4)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.



```
{ 
   c0fd557 (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
31683a9 (origin/main, origin/HEAD, main) Update LAB_INSTRUCTIONS.md
c05d49a Merge pull request #79 from JeffSinsel/typoFix
301ee3e Update LAB_INSTRUCTIONS.md
20e50ed fixed typos
1ac4149 Update LAB_JeffSinsel.md
b239f80 Complete lab report minus git logs
56d3062 yo @trevordbunch
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
(END)
}
```

```
{ 
3f34e6e (HEAD -> main, labreport) Commiting changes of lab steps up to 6, one commit of step 4 did right before this one
af10704 (origin/labreport) your commit and reference @trevordbunch in the message
c0fd557 your commit and reference @trevordbunch in the message
31683a9 (origin/main, origin/HEAD) Update LAB_INSTRUCTIONS.md
c05d49a Merge pull request #79 from JeffSinsel/typoFix
301ee3e Update LAB_INSTRUCTIONS.md
20e50ed fixed typos
1ac4149 Update LAB_JeffSinsel.md
b239f80 Complete lab report minus git logs
56d3062 yo @trevordbunch
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
(END)
}
```

```
{
   10d7d89 (HEAD -> main, labreport) fixed link to correct diagram
ddd69b7 (origin/labreport) More Markdown Formatting editing, fixed link to feature branch diagram
a73137b (origin/main, origin/HEAD) Markdown Formatting editing, fixed layout on file
3f34e6e (origin/labreport) Commiting changes of lab steps up to 6, one commit of step 4 did right before this one
af10704 your commit and reference @trevordbunch in the message
c0fd557 your commit and reference @trevordbunch in the message
31683a9 Update LAB_INSTRUCTIONS.md
c05d49a Merge pull request #79 from JeffSinsel/typoFix
301ee3e Update LAB_INSTRUCTIONS.md
20e50ed fixed typos
1ac4149 Update LAB_JeffSinsel.md
b239f80 Complete lab report minus git logs
56d3062 yo @trevordbunch
50d40f8 Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
(END)
}

```

Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

[Branch](https://drive.google.com/file/d/1oKyWRueneaLRrnaiBkS3lMdFad529wOj/view?usp=sharing)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.