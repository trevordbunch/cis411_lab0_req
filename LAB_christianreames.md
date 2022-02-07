# Lab Report: Continuous Integration
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Christian Reames  
**GitHub Handle:** christianreames
**Repository:** Your Forked Repository
___

# Step 1: Fork this repository
- The URL of my forked repository: https://github.com/christianreames/cis411_lab1_CI.git
- The accompanying diagram of what my fork precisely and conceptually represents... 
(https://docs.google.com/drawings/d/e/2PACX-1vSv9fE-v4XKkS6u10ch3xICimcLSdm1n0J5NoUmrK2dRQV3ankMxf0BJGQkdxEjJImdc0FgEll_UUs_/pub?w=960&h=720)

# Step 2: Clone your forked repository from the command line  
- My local file directory is... /Users/christianreames/cis411_lab1_CI
- The command to navigate to the directory when I open up the command line is...
cd

# Step 3: Run the application locally
- My GraphQL response from adding myself as an account on the test project
``` json
{
  "data": {
    "mutateAccount": {
      "id": "13f6c3da-c4a5-4341-a181-fedb98fb77e4",
      "name": "Christian Reames",
      "email": "cr1368@messiah.edu"
    }
  }
}
``` 

# Step 4: Creating a feature branch
- The output of my git commit log
```  
2bcf195 (HEAD -> labreport, origin/labreport) your commit and reference @trevordbunch in the message
7490dcb (origin/main, origin/HEAD, main) Add Links to Node in Instructions
ecaaa53 Update branch terminology
c552213 Merge pull request #3 from hallienicholas/main
78ede9f Corrected error
1fe415c Merge pull request #1 from trevordbunch/labreport
13e571f Update Lab readme, instructions and templates
eafe253 Adjust submitting instructions
47e83cd Add images to LabReport
ec18770 Add Images
```
- The accompanying diagram of what my feature branch precisely and conceptually represents...
(https://docs.google.com/drawings/d/e/2PACX-1vRgquJLVYmkZH-G390RSVjtn1MLr70uyv12iDlz3P1CgJGf0Wsek6SRWnuySd7_AHHnpevjpJvvUEs2/pub?w=960&h=720 )

# Step 5: Setup a Continuous Integration configuration
- What is the .circleci/config.yml doing?  

.circleci is the name of the directory where config.yml is stored. config.yml 

- What do the various sections on the config file do?  

The version specifies the version that's being used. Build is a defined job. Inside of a build is where the docker container is and it uses a native language circlci and the version of node (version-- node 10.3).  

- When a CI build is successful, what does that philosophically and practically/precisely indicate about the build?  

People can access or add to the build wherever and whenever they want. It doesn't matter what system they use. 

- If you were to take the next step and ready this project for Continuous Delivery, what additional changes might you make in this configuration (conceptual, not code)?  

In order for the project to be able to be ready for continious delivery, Applications and updates must be able to be released at any time. It is also important that users can easily give feedback to developers to make quicker changes. 

# Step 6: Merging the feature branch
* The output of my git commit log
```
60d45f9 (HEAD -> main, labreport) commitmessage
2bcf195 (origin/labreport) your commit and reference @trevordbunch in the message
7490dcb (origin/main, origin/HEAD) Add Links to Node in Instructions
ecaaa53 Update branch terminology
c552213 Merge pull request #3 from hallienicholas/main
78ede9f Corrected error
1fe415c Merge pull request #1 from trevordbunch/labreport
13e571f Update Lab readme, instructions and templates
eafe253 Adjust submitting instructions
47e83cd Add images to LabReport
ec18770 Add Images
dbf826a Answer Step 4
a9c1de6 Complete Step 1, 2 and 3 of LAB_TREVORDBUNCH
1ead543 remove LAB.md
8c38613 Initial commit of labreport with @tangollama
dabceca Merge pull request #24 from tangollama/circleci
a4096db Create README.md
2f01bf4 Update LAB_INSTRUCTIONS.md
347bd50 Update LAB_INSTRUCTIONS.md
7aaa9f3 Update LAB_INSTRUCTIONS.md
37393ae Bug fixed
1949d2a Update LAB_INSTRUCTIONS.md
:

...
44ce6ae Initial commit
(END)
```

* A screenshot of the _Jobs_ list in CircleCI
![CircleCI Success](https://docs.google.com/document/d/e/2PACX-1vQP52JuN_YhFy1Pe29g7XAYubQeGOffCQn49PdKyMAWiRncumvSmt8bxU9UQlULVdcZg5smxUrQVL8V/pub)

# Step 7: Submitting a Pull Request
_Remember to reference at least one other student in the PR content via their GitHub handle._
@Cmcculler1


# Step 8: [EXTRA CREDIT] Augment the core project
PR reference in the report to one of the following:
1. Add one or more unit tests to the core assignment project. 
2. Configure the CircleCI config.yml to automatically build a Docker image of the project.
3. Configure an automatic deployment of the successful CircleCI build to an Amazon EC2 instance.
