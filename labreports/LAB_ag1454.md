# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Abigail Garrido  
**GitHub Handle:** ag1454  
**Repository:** https://github.com/ag1454/cis411_lab0_req  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

Business problem: “I would like to order a meal from an on-campus provider and have it delivered to my classroom.”

![Business Process](/assets/BPD.PNG) 

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

- **Business**
	- B.1 The system will prevent users from placing orders after 7 PM. The system will also prevent users from placing orders during peak mealtime hours. (Jennifer)
	- B.2 The system must provide a way to disable the delivery option in the event that staff capacity is low. (Jennifer)
	- B.3 The system must pad the anticipated delivery time by five minutes. (Jennifer)
	- B.4 The system must have a maximum number of accepted deliveries. Once it reaches that number, it prevents users from ordering until at least one order has been delivered. (Jennifer)
- **User**
	- U.1 The user must be able to input their location into the system. (Rebekah)
	- U.2 The user must be able to access the system through FalconLink, similarly to how users are able to order food from Union through FalconLink. (Rebekah)
- **Functional**
	- F.1 The system must display the user’s account balance. (Loki)
	- F.2 The system must allow for order cancellations before placing the order. (Loki)
- **Non-functional**
	- N.1 The system must include pictures of the available food options. (Thor)
	- N.2 The system must use a color scheme that doesn’t hinder the ability to read text or identify pictures and icons. (Thor)
- **System**
	- S.1 The system must be able to be accessed from desktop and mobile. (Randy)
	- S.2 The system must have dedicated hardware. (Randy)
	- S.3 The system must be secure in order to protect user information. (Randy)
	- S.4 The system must be able to handle as many accounts as there are students and employees. (Randy)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.* 
![Diagram](/assets/Diagram.png)  

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.


###### Step 2.7
```
0446319 (HEAD -> labreport) commit2, ref @trevordbunch
505ed41 (origin/labreport) commit1, ref @trevordbunch
50d40f8 (upstream/main, origin/main, origin/HEAD, main) Update references to main branch
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

###### Step 6.4
```
cd5e776 (HEAD -> main, labreport) commit8
09c6d2a (origin/labreport) commit7, ref @trevordbunch
173f7d9 commit6, ref @trevordbunch
ee1aff5 commit5, ref @trevordbunch
ce06ee4 commit5, ref @trevordbunch
77be37b commit4, ref @trevordbunch
05e2f88 commit3, ref @trevordbunch
0446319 commit2, ref @trevordbunch
505ed41 commit1, ref @trevordbunch
50d40f8 (upstream/main, origin/main, origin/HEAD) Update references to main branch
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
![Relationship](/assets/Relationship.png)  

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.

(I did 8.2.)