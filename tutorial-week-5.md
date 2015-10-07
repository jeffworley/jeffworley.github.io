### Brainstorming Outline v1.0:

##### What Should I Teach?
* Git from the Command Line

###### What Should I Cover?
* What is Git?
Git is a versioning control system.
* How to Install it.
Visit [_this_](http://git-scm.com/download/mac) website and follow the instructions.  Don't worry they are straight forward.
* What it is used for (briefly).
Git is used to maintain and track software project progress.  I will go into more of what this means tonight.
* How to create a branch locally.
`git branch </somebranchnameyouwant>`
* How to checkout that branch.
`git checkout </branchyouwant>`
* How to make a commit.
1. `git status`
2. `git add </files you want to track>`
3. `git commit -m </short message regarding what you did for this commit>`
* How to merge the new branch back with the master.
`git merge </branchyouwanttomerge> </branchwhereyouwanttomergeinto>`

###### Why is this Relevant/Important?
* Track our progress.
* Share our code (eventually).
* Experiement without hurting the master (production).
* Great for teams of teams working on different parts of the same project.
