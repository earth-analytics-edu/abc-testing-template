# abc-classroom starter template

This is a repository created to test abc-classroom functionality. It is intended for abc-classroom developers / testers. Being able to effectively run all of the abc-classroom scripts requires a fair bit of setup in advance. This repo tries to give you a good start.

## Setup notes

These are the steps taken to generate this repository.

On local machine, at the command-line:

* run `abc-quickstart abc-testing-template`
* cd `abc-testing-template`
* update the github organization in `config.yml` to `earth-analytics-edu`
* create an nbgrader course: `nbgrader quickstart nbgrader`
* cd `nbgrader`
* create an nbgrader assignment: `nbgrader db assignment add test-abc-1 ` and `mkdir source/test-abc-1`
* git stuff: initialize as a git repo, commit everything, change the local branch name to main, and push to github

To get started with testing, you also need to setup a class on [GitHub Classroom](https://classroom.github.com):

* create a new github classroom called `abc-testing-class` in the `earth-analytics-edu` organization (skipping the addition of TAs and admins for now)
* add [Karen Cranston, Leah Wasser, Nathan Korinek] as students (using full names as identifiers)
* add an assignment called `abc-testing-1` (settings: no deadline, individual assignment, private repo, do not grant students admin access to their repos)
