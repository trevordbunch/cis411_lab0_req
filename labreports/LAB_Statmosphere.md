# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Andrew Roberti  
**GitHub Handle:** Statmosphere  
**Repository:** [https://github.com/Statmosphere/cis411_lab0_req](https://github.com/Statmosphere/cis411_lab0_req)
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

[Overview](https://docs.google.com/drawings/d/1VDu_ld4At0VCpFynmWMAJt0gCKbox0nXDtkzaEOdEm8)



## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

    (My interviewees were students, Mike Shoul and Ben Clarke. Requirement requests were made together.)
    Business:
        The order must take no more than 10 minutes from the time it is ordered until it gets delivered. The system will therefore limit the orders placed based on the amount of staff present.
        Food will be packaged in a manner that keeps it warm throughout the delivery process.
    User:
        The user only needs a laptop or mobile device to access the website.
        To place an order, the student needs to specify what food items they want and a location for the food to be delivered to.
    Functional:
        The system will automatically pay for the student via the student's Dining Dollars.
        Upon placing an order, the system needs to return an expected wait time, taking into account the other orders already placed and the staff available.
    Non-Functional:
        The system must not have lower loading times than other digital food ordering services on campus (such as those used by The Union and The Falcon). The point of this service is to be more convienent than going in person and placing an order.
    Service: (Nothing was specified by Mike or Ben, but I have one thing to add.)
        The system shall use the same CAS system used by Messiah services such as Falcon Link so that the student logs in before accessing the website.

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*
[Diagram] (https://docs.google.com/drawings/d/16Tjh7aHllE7MXwTrK7L2gaA3AYvptTY0PzrY0M58mkE)

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

Step 2.7
```
9bf6b16 (HEAD -> labreport, origin/labreport) Step 2.7
40e0763 August 6th Reset
4086659 Update LAB_Statmosphere.md
3f28597 my second commit
1f5c27d my first commit
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
```
Step 6.4
```
596c761 (HEAD -> labreport, origin/labreport) Step 6
e3567a4 August 7th Marker 1
9bf6b16 Step 2.7
40e0763 August 6th Reset
4086659 Update LAB_Statmosphere.md
3f28597 my second commit
1f5c27d my first commit
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
```

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)
[Diagram] (https://docs.google.com/drawings/d/1oWactPk_4w9WXOxuGEVo6n54NaVpL6yehXowyv9IL4I)

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.