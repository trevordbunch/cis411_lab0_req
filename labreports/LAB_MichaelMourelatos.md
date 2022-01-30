# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Michael Mourelatos  
**GitHub Handle:** MichaelMourelatos  
**Repository:** [MichaelMourelatos Forked Repository] (https://github.com/MichaelMourelatos/cis411_lab0_req)
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

**Business Overview**: Students, staff, and guests can access the online dining service, The Falcon, through connection of the Messiah Network. Being able to process payments via online allows for people to be more efficient throughout their day. The site will allow users to be able to send orders online and be able to be notified when the food is ready to be picked up. The payments and orders are processed by The Falcon through the site user login information through the network.

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

**Business**:
-	The University’s system must be capable of processing multiple orders online at once (Falcon Manager)
-	The University’s system must update the system based off available items (Union Manager)
-	The University must have enough staff for breakfast and lunch (Falcon Manager)

**User**:
-	Users must make payments using their school ID, cash, or credit (Falcon Manager)
-	Users must be connected to the network (Union Manager)
-	Users must place a time for pickup (Union Manager)

**Functional**:
-	Must have an interface to show the food items (Union Manager)
-	Confirmation of order sent to email (Falcon Manager)
-	Sending an Email when ordered is ready (Falcon Manager)

**Non-Functional**:
-	The system must be capable of processing 500 orders within each hour of being open (Falcon Manager)
-	The system must have “cancel”, “go back”, and “proceed to checkout” options (Falcon manager)
-	The system must remove unavailable items (Union Manager)
-	The system must provide images of the items (Visual Learner #1)

**System**:
-	User can only access the website when connected to the Messiah Network (Andrew Coldsmith)
-	The system must process that the user’s ID Card matches the receipt through scanning (Andrew Coldsmith)


## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

```
aed6d07 (HEAD -> labreport, origin/labreport) Michael Mourelatos making first commit to @trevordbunch.
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


Hint: for system output, use markdown's fenced code block for formatting.

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.