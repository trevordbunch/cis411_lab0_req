# Lab Instructions

## Step 0 - GitHub Account and Prerequisite
1. If you don't have a GitHub account already, [create one](https://github.com/join). If you do, record the name of your handle in your lab report.  
> Note: When you choose a handle, please consider that your handle will eventually become part of your professional persona (e.g., this will go on your resume).
2. If you don't already have _git_ installed on your development machine, [do so](https://git-scm.com/downloads).  If you struggle with command line interfaces (CLI), then you will be able to do most of this lab using [GitHub Desktop](https://desktop.github.com/); it will install _git_ as part of the package.  _Eventually, you will need to get comfortable with git CLI._
3. Install a text editor or some sort of application for local development. Lately, I'm partial to [Visual Studio Code](https://code.visualstudio.com/) and my instructions assume it's use, but you're welcome to deviate. If you do choose Visual Studio Code, I recommend installing a couple of extensions: 
   1. [`Markdown All in One`](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) allows you to use keyboard shortcuts (e.g., `Ctrl` + `B`) to apply formatting.  
   2. [`Markdown Preview Github Styling`](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) will let you preview your markdown prior to committing and pushing it to GitHub.



## Step 1 - Fork this repository
1. After logging in, navigate to the root of this repository.
2. Fork this repository to your personal GitHub account (hint: read the page).
3. Record the URL to your forked repo in your lab report.
4. Generate a simple diagram (in Google Draw or your favorite diagramming tool) that demonstrates the relationship between this repository and my account (trevordbunch) with your account and your newly forked repository. (i.e. Is this the same thing as a source control branch or is there something unique about a fork in a distributed version control system? Hint... I'm asking for a reason. If it's helpful, think about the relationship you and another student who is conducting the fork command each has to this repository.)
5. Now pull your forked repository down to your local machine using the following command `gh repo clone [GITHUB USERNAME]/cis411_lab0_req`.

## Step 2: Creating a feature branch
[Branching and merging](https://www.atlassian.com/agile/software-development/branching) is a common tactic used in change management and feature development. We're going to use a branch (and eventually a merge) to build our lab report.

1. Create the branch `git checkout -b labreport`.
1. Create a lab report markdown file (ex. `cp labreports/LAB_Template.md labreports/LAB_[GITHUB USERNAME].md` ).
1. Add your lab report `git add *`
1. Add the file to your branch `git commit -a -m "your commit and reference @trevordbunch in the message"`.
1. Push the change to GitHub `git push -u origin labreport`.
1. As you make additional changes to the lab report, commit and push at least one more change to the branch.
7. Add the output of your git commit log for your feature branch to your lab report `git log --oneline`.
8. Generate a simple diagram that demonstrates the relationship between your main and feature branch in your forked repository.

## Step 3 - Interview Stakeholders
Find at least two humans to discuss the following business need.  
```
“I would like to order a meal from an on-campus provider, 
and have it delivered to my classroom.”
```

If there are any gaps that you are perceiving in fully understanding the business problem, please feel free to fill in the gaps with fictional personas or documentation.

## Step 4 - Summarize
After collecting your interview data, assemble the results into a single overview processes.  If necessary, repeat interviews to fill in gaps or document alternative outcomes.  The goal is to get an end-to-end picture of the business problem that you are solving, and provide an organizing frame to start to tackle it.

## Step 5 - Document Requirements
Using your *Step 4* summary as a guide, start organizing and formulating your requirement statements into the body of your lab report.  You have some flexibility in how you organize and present this in the template.

## Step 6 - Merging the feature branch
1. Commit your changes to your feature branch ```git commit -a -m "your commit message```.
2. Switch to the main branch ```git checkout main```.
3. Merge the changes from your feature branch ```git merge labreport```.
4. **Add the output of your git commit log** from main to your lab report ```git log  --oneline```.

# Step 7: Submitting a Pull Request
Once you've completed your report markdown, have ensured that your forked repository is successfully running in CircleCI, and have committed all your changes to your (primary) main branch, initiate a Pull Request in GitHub to submit your Lab Report.
1. Navigate to the root of your forked repository (ex. https://github.com/YOURHANDLE/cis411_lab0).
2. Click the _New pull request_ button.
3. Choose the base fork _trevordbunch/cis411_lab0_req_ is the target and that your fully updated _main_ branch is the source.
4. Enter a title and description for the Pull Request (PR), **referencing at least one other student in the content via their GitHub handle**, and submit the PR.

## Step 8 - Extra Credit
1. Provide a diagram that shows the round-trip that the code has made during this lab, starting and ending with source repository.  Document all fork, branch, commit, merge and pull request actions in your diagram.
2. Find a typo, fix it and submit it in a separate `pull request`.
