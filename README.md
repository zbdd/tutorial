# Tutorial 1
A introduction to programming and the common tools you need to make your coding life a bit easier.
The basic idea will be to iteratively complete each part, building towards a larger more fully functional piece of software. This approach will reinforce clean coding principles as you move from coding solutions to software design.

### Acceptance criteria
* Learn a bit about source control by using git
* You need to send me the URL of your forked repo.

### Steps
1. Install [git](https://git-scm.com/)  or you can also use a git GUI like [git desktop](https://desktop.github.com/)
2. Create an account on [github](https://github.com/)
3. [Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) this repository
4. [Clone](https://github.com/git-guides/git-clone) your fork
5. Create a [branch](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) called 'tutorial-1' off main
6. [Push](https://github.com/git-guides/git-push) your branch to Github

### What is git?

**git** is a command-line version control system. It consists of **commits** that chain together to form the history of your code.

What is unique about **git** is it's implementation of **branches** which are copies of your code (including **commit** history) from where you branched off from.

You can work on these **branches** independently of one another, and then **merge** them back into a **main** branch when ready.

![image](https://github.com/zbdd/tutorial/assets/3454727/c1565d8a-4395-4290-b477-6ced6f1e72c6)
_a simple project with two commits_

![image](https://github.com/zbdd/tutorial/assets/3454727/4b5fd339-2382-4579-8bca-0e4f06db8428)
_after another small change to the value of count, we save our progress by making another commit_

![image](https://github.com/zbdd/tutorial/assets/3454727/aea19458-cf2d-42d0-90c9-2610631093f7)
_developer 2 decides to create their own dev branch from the HEAD of the main branch and has made one unique commit_

![image](https://github.com/zbdd/tutorial/assets/3454727/0dd0d4c8-8682-4717-a549-0e2f96573d49)
_meanwhile, a bug was found and developer 1 creates a new hotfix branch and has made one commit to fix the problem_

![image](https://github.com/zbdd/tutorial/assets/3454727/23a5179a-1c16-457e-9eaa-1b71afcf9cba)
_the fix is good, and the commit FIX is merged into main and becomes the new HEAD, seperately, developer 2 creates another commit to their branch_

![image](https://github.com/zbdd/tutorial/assets/3454727/35712455-da3d-46f7-afdc-a93c151b70c2)
_developer 2 is ready to merge their branch into main, git does a three way merge between the commits FIX, DEV1B and their common ancestor DMG3 to create the new merge commit DMG4_

