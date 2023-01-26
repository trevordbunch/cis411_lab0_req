# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Your Name  
**GitHub Handle:** Your GitHub Handle  
**Repository:** Your Forked Repository  
___

## 1. Overview
In this section provides a brief overview of the business problem.  By brief, it should include a single image (business process or use case diagram) and a textual explanation (describing actors, tasks, information, or outcomes) and described in *Step 4*.

#### Response

![Use Case](/assets/UseCase.png)

___

## 2. Requirements
In this section, organize and list requirements from *Step 5*.  You are welcome to organize this section in anyway that you would like (using headings or tables).  The structure of this section should correspond to your overview section, and it is recommended that that you review the [lessons learned](../lessonsLearned.md) from your colleagues.

#### Response:

- **Business**: The business objective that the system needs to satisfy.
    - Bus.1 The system must inform customers upon a staff shortage, to accommodate the additions to the Covid Low-Employment delivery Service Level Agreement. (Pointy Hair Boss)
- **User**: The actions that a user takes within the system
    - User.1 The user must associate their account with payment method, including Dining Dollars, Falcon Dollars, Credit Card, and PayPal. (Hungry Student 1)
- **Functional**: The functions should the system perform
    - Fun.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order. (Hangry Student 2)
    - Fun.2 The system must notify the user about unsafe weather conditions and how the anticipated delivery time is extended or uncertain. (Aidan)
- **Non-Functional**: The characteristics that the system should have.
    - Non-Fun.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
    - Non-Fun.2 The system must maintain an order and payment processes if the application crashes. (Upset student 1)
- **System**: Specifications about how the system should be built.
    - Sys.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
    - Sys.2 The system must use Messiah University's Multi-factor Authentication for secure a sign on process. (Cybersecurity Professor)
___

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

#### Response:

- **User**:
  - User.2 The user should be able to make payments throughout a period of time. (Justin)
- **Out of Scope**:
  - THe system must display the geolocation of the delivery method, displaying its speed and orientation. (Ray)

___

## Appendix: GitHub Notes

### A.1 Forked Repository
In this section, provide a diagram that demonstrates the relationship between the [source repository](https://github.com/trevordbunch/cis411_lab0_req) and your forked repository in *Step 1.*  

#### Response:

![Use Case Diagram](/assets/fork_diagram.png)

___

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.

Hint: for system output, use markdown's fenced code block for formatting.

#### Response:
##### Step 2.7 Logs
```
9a9d4e6 (HEAD -> labreports, origin/labreports) your commit and reference @trevorbunch in the message
2ce0103 (origin/main, origin/HEAD, main) Add files via upload
d3575ed Delete diagram.pdf
e202670 Add files via upload
50d40f8 (upstream/main, upstream/HEAD) Update references to main branch
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

#### Step 6.4 Logs
```
2436ff1 (HEAD -> main) Merge branch 'labreports'
60b4ab9 (origin/labreports, labreports) commit message
9d33283 (origin/main, origin/HEAD) Add files via upload
9a9d4e6 your commit and reference @trevorbunch in the message
2ce0103 Add files via upload
d3575ed Delete diagram.pdf
e202670 Add files via upload
50d40f8 (upstream/main, upstream/HEAD) Update references to main branch
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
___

### A.3 Branch Repository
In this section, provide a diagram that demonstrates the relationship between your main branch and your feature branch in your repository (*Step 2.8*)

#### Response:
```
214c724 (HEAD -> main) Merge branch 'labreports'
66f2a37 (labreports) commit message
2436ff1 Merge branch 'labreports'
60b4ab9 (origin/labreports) commit message
9d33283 (origin/main, origin/HEAD) Add files via upload
9a9d4e6 your commit and reference @trevorbunch in the message
2ce0103 Add files via upload
d3575ed Delete diagram.pdf
e202670 Add files via upload
50d40f8 (upstream/main, upstream/HEAD) Update references to main branch
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

![Use Case Diagram](/assets/Branch Diagram.png)
___

### A.4 Extra Credit
In this section, provide the round-trip diagram described in *Step 8*.

#### Response:


___