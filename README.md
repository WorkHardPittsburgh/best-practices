# best-practices

# Work Flow for Web Apps

Here is a process (that is in process) for contributing to the to-be-named app for GSNI.

## Create a card in Asana

* Look through the current cards in Asana
* Consider the requirements of the milestone
* Create a card to represent a single aspect of the app
* Put any subtasks in that card
* Mark it with the tag for the correct milestone
* Assign it to yourself if necessary
* Put it in the "Doing/ Current Sprint" column

## Create a branch in the Github Repo

* Make sure your master is up to date (git pull if not)
* Create a branch for the aspect of the app that you are working on
* Try to name it in a way that relates to what you are doing, fixing, or working on
* After you have made some changes (sooner, rather than later) create a pull request for the branch and lable it "work in progress"

## Tests
* To be added

## Get ready for a code review of your branch

* Change your comment in the pull request to "ready for review"
* Add notes to the pull request as needed, for example, specifying what the branch is doing, what a reviewer should be testing and checking, why things were done the way they were,and the context
* Assign reviewers to the review
* Move the card in Asana to internal review
* Include a link in the Asana card to the pull request (in Github)

## After your code is reviewed

* Make all changes
* Recommit
* After the pull request is approved (and not before), merge it into master
* After the pull request is merged, delete the branch in the github repo
* Delete the branch in your local repo

## When reviewing the code of others

* Be specific and clear
* Include screenshots if relevant

## Issues

* If you notice problems with something in the app, open up an issue
* To fix an issue, first assign yourself to it
* Create a branch and an asana card (see above)
* In the pull request, link to the issue
* In the issue, link to the pull request
