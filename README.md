# Short Training

###Objective

1. Master git fundamental skill.
2. Introduction to SCRUM methodology.
3. Introduction to Material Design Concepts.

###Duration

1. <b>ONE</b> week.

###Cooperative tools

1. Trello
2. Slack

###Material Design Template

1. Material Design Lite - for more details visit http://www.getmdl.io/templates/blog/index.html

###Training project

1. Simple blog by using material design concept.

###Contribute

- ```git clone git@github.com:jk-gan/training.git``` into your directory
- ```git checkout -branch *your_branch_name*```
- Commit your work to your own branch ```git push origin *your_branch_name*```
- Make sure to check if there are any changes from remote master, and rebase your branch with the latest master
  - ```git fetch```
  - If there are some uncommitted changes, stash your work before rebase ```git stash```
  - ```git pull --rebase origin master```
  - Fix merge conflicts (if any?)
  - After rebase then ```git stash pop``` to bring back all uncommitted changes
- Submit a pull request, and write descriptive comments.