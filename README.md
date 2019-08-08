# Git for Web Development Project

In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:

You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your PM as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [ ] Run your usual git commands for adding/commiting and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:

Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [ ] Add your PM as a collaborator to your fork.
- [ ] Go into your project folder, make a new branch `firstname-lastname`
- [ ] Add your first and last name to the README.md file in the project and save.
- [ ] add/commit/and push to your own branch **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch

- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independantly research the following topics to learn more about Git.

  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Reseach the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Reseach the Git commands `reset`, `revert`, `clean`. These commands will allow you to go back and ammends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console.

- [ ] Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push.

### Merge Conflict

A merge conflict is when you try to merge code from one branch into another, but the changes from your branch conflict with the changes on the base branch.
Taken from Git Tower, a merge conflict occurs "if two people changed the same lines in [the] same file, or if one person decided to delete [the file] while the other person decided to modify it."

### Pull, Rebase, and Merge

- When you `git pull`, you bring in the latest changes from the remote repo into your local repo. `git pull` uses `git merge` to incorporate changes.
- When you `git rebase`, you take all the changes from one branch and replay them onto another branch, creating a unified history of the two branches.
- - From the official git documentation: "This operation works by going to the common ancestor of the two branches (the one you’re on and the one you’re rebasing onto), getting the diff introduced by each commit of the branch you’re on, saving those diffs to temporary files, resetting the current branch to the same commit as the branch you are rebasing onto, and finally applying each change in turn."
- When you `git merge`, you incorporate all the commits of one branch into another branch at that branch's head.
