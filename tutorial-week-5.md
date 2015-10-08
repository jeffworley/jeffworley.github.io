### Rough Draft v2.0:

##### What Should I Teach?
* Git from the Command Line

###### What Should I Cover?
* What is Git?
Git is a versioning control system.

* How to Install it.
Visit [_this_](http://git-scm.com/download/mac) website and follow the instructions.  Don't worry they are straight forward.

* What it is used for (briefly).
Git is used to maintain and track software project progress.  This sounds like a simple concept and it is but mastering it is a whole other beast.  As developers we need to be responsible when we interact with the teams code and one way to do that is to use a VCS like git.  It allows us to take the code we are working with as a collective and put it in a _sandbox_ to make adjustments to and test without risk of hurting the overall project.  It also, allows us to be flexible in our project progress as it logs different iterations/states of our project for retrieval or review at later times.  This is just an intro so we will leave it at that for now.

* How to create a branch locally.
A branch is that _sandbox_ I referenced above.  If you think of projects like a tree, the trunk is the production code (and therefore the most sensitive to risk) and a branch is everything the trunk is plus what you add to it.  It cannot be part of the trunk (_master_) until approved by your VCS manager.
`git branch </somebranchnameyouwant>`

* How to checkout that branch.
Once you have created a branch, you then want to check it out so that you can begin to work in that enironment/version of the code.
`git checkout </branchyouwant>`

* How to make a commit.
1. `git status` //This lets us know what files have changed, which are tracked, and which need to be tracked by the VCS.
2. `git add </files you want to track>` //This command followed by file names or directories with files in them readies our VCS for their storage and logging.
3. `git commit -m </short message regarding what you did for this commit>` //This creates an "picture" so to speak of your current work in the VCS and should be done frequently to prevent having to dig through mounds of code to find an error.

* How to merge the new branch back with the master.
`git merge </branchyouwanttomerge> </branchwhereyouwanttomergeinto>` //This is a step a bit futher down the road but is essential for when you have a significant contribution to your overall project and are finished working with it in isolation.

###### Why is this Relevant/Important?
* Track our progress.
* Share our code (eventually).
* Experiement without hurting the master (production).
* Great for teams of teams working on different parts of the same project.
