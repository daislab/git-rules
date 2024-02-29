# git-rules
DAIS protocol for contributions. Here you can find the guidelines for participating in a DAIS git-project.


Please follow the steps I've included to add changes in a project.

## A. Creating a new ISSUE 

### Steps:

1. Create an Issue describing the new feature or the problem you want to fix.
2. Claim that you will fix the issue. In the right layout of the issue, you can manage who will be assigned for an issue.
3. Follow the [steps](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-a-branch-for-an-issue)
to create a branch associated with that issue. It is recommended to create a new branch which starts from the main.

### Managing branches:

In general, you can manage your branches locally. Get a list of the existing branches:

> git branch

Change to your preferred branch:

> git checkout \<branch-name\>


Creating a branch from the current branch:

> git checkout -b \<new-branch\>

Specify the name of the branch

> git checkout -b \＜new-branch\＞ ＜\existing-branch\＞

When pushing first time from a branch that was created locally:

> git push --set-upstream origin \<branch-name\>

Checkout to a remote branch:

> git fetch --all
> git checkout \＜remotebranch\＞


## B. In-branch commits


## C. Passing updates to main

 -  3.1 Clean commits


 -  3.2 combine to main


 -  3.3 Remove branch

 Once the issue is closed and the changes have been passed to the main branch you can delete the branch. 
 First, delete the branch locally using the following command:

 > git branch -d \<branch-name\>

Then push this action to remote repository:

> git push origin -d \<branch-name\>


 ## Coding rules
General comments for the codes overview
**Prototypes**

**Comments**
