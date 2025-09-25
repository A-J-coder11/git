GIT
=====
create a repo
create some files and folders in the repo
add to staging area
commit to local repo
push to central repo


clone the repo
pull the changes


git init --> intialize the folder as git --> create .git in a folder
.git --> if your folder have this, then we call it as repo


git branch -M main
git remote add origin <remote-URL>

brances
pull request
merge
Rebase
How to resolve conflicts
Branching strategy

==================================
PROD --> main/master branch

create new brancg
DEV QA UAT SIT PERF PRE-POD PROD

build and deploy in DEV
Run the test cases
Move to QA/UAT/SIT
Run the test cases

Then take the approval from the CR process
Then deploy to PROD


=============================================

git init
git branch -M main
git remote add origin <url>
git add . ; git commit -m "git" ; git push origin main

====================================================



 - git 
  -  settings
   -   ruleset
    -    new ruleset
           new branch ruleset
          name - main-branch
          enforcement status - Active
          Target branches - 
            Add Target - include by patter - Branch name pattern // give main - add inclusion
          Rules
            - Restrict deletions
          Require a pull request before merging
            - Required Approvals - // give according to the dv siz if 10 give 4
          Block force pushes

  - create

==================================================

creating a new branch
  -> git checkout -b plain-dosa //plain dosa branch will be created

  -> git logs // will show commits done 