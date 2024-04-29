# Git Assignment - IhorKyl

a. What is an issue?
GitHub issues are an extremely useful tool for communicating decisions, ideas and
problems that are project specific.

b. What is a pull request? A pull request is a mechanism for proposing changes to a repository and requesting that those changes be reviewed and merged into a target branch, typically the main branch.

c. How do I open up a pull request?
 1.Go to repository of the project
 2.Press "branches" button which located at the menu under name of repository.
 3.At the branch you want to merge press "..." and then "New pull request" .
 4.Check base and compare branches for proper merging beetwen branches. Fill precisely description of what you did.
 5.Press "Create pull request"
 
d. Give me a step by step guide on how to add someone to your repository.
1.Go to repository.
2.At the top menu press Settings "gear" icon.
3.Choose "Collaborators" under the rop menu.
4.Press "Add people" green button.
5.Tag collaborator using "@"<username>
6.Press green confirmation button "Add <suername> to tis repository"

e. What is the difference between git and GitHub?
Git is the version control system itself, while GitHub is a platform built around Git that adds collaboration and project management features.

f. What does git diff do?
Git diff compares what is in our working directory to what is in our staging area. If we've made changes to our files without running git add , we'll see the comparison. If there are no differences, nothing will be shown.

g. What is the main branch?
The main branch serves as the starting point for development and often reflects the most stable version of the project. Developers typically create feature branches from the main branch, work on new features or fixes, and then merge those changes back into the main branch once they are completed and tested.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
It's strongly not recomended however technically possible to push changes directly to the main branch. Following a branching strategy and utilizing pull requests for code review and integration offers several benefits in terms of collaboration, code quality, and stability.