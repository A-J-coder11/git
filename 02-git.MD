<!-- Branching startegy -->
  what are the branches
  How you bring chnages from DEV to Prod
  other branches to main/master branch

  GIT FLOW
  FEATURE BRANCH --> MAIN MERGE - agile methdology microservices
  trunk based

  long lived branches
  short lived branches


  main/master - PROD //production branch

  devlop -> in this branch we can see what is going on
  =======

  source: main/master
  destination: main/master

  feature -1
  =======
  source: develop
  destination: develop

  clone - build - unit test cases - scan - create images - push image

  successfully merge into master

  feature -2
  ==========
    pull the changes from develop
    merge/rebase
    raise PR and merge to develop

    release = New features + bug fixes + improvements

  Realease branch
  ==============
  source: develop
  destination: master and develop
  life time is until that relase is successfully sent to prod. you  get the changes to master/main

  deploy into the environments DEV QA UAT and test the application
  if there is any bug fixes here only
  deploy to PROD. if succesfully deployed then you merge these chanegs into master/main

  you can delete release branch when it is succesfully deployed into PROD

Hotfix
======

priority-1 --> max 4 hours --> buissness is getting affected

source: main
destination: develop and main

hotfixes-emergency-ticket-price --> approval from the charimen/CEO

test in develop once and then deploy to PROD. you need to get chnages to main and develop both

featuring branching strategy
=============================

web application will not have version

feature
  clone - build - unit test cases - scan - create images - push image
  merge to main --> QA UAT SIT PROD
  main -> hotfixes -> deploy to DEV -> merge the changes to main -> deploy to PROD
