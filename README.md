# GitHub Tutorial

_by Derek Conde Barranco_

---
## Git vs. GitHub
###Git
* `Git` is version control by keeping **"snapshots"** of code
   * Runs in the command line but doesn't require github. 

###Github
* `Github` stores your code in the cloud(**internet**) and is used to check changes from Git.
    * `Github` is also used to collab with others on the same files.
    * Can be used to interact with code and snapshots from Git.
    * Runs in the command line
     * Uses git to interact with code from the snapshots     
---   
## Initial Setup
1. To first start setting up your github, you mush create an account on [github.com](http://www.github.com)
   * _Requires an email and password in order to sign up._
   * _You also need to create a username for your_ `github`
2. Make sure that have already setup your local machine with an IDE (**ex:nitrous and cloud 9**)
3. Inside of your IDE on your local machine, `git config --global username` "**Insert your username here**"

---
## Repository Setup



---
## Workflow & Commands
* `git init` Calls your directory, repo for version control
* `git status` View what files have been edited so far or that need to be committed
* `git add file.ext` Adds the file to the stage for it to be committed(**snapshot**)
* `git add . ` Adds entire directory to the stage.
* `git commit -m "short/specific message"` Commits the file and write a small message with it
     * You need to write a message to the commit or else it will not work
* `git log` See your past commit
* `git help` gives you help with commands in case you forget
* `git diff` View the difference between your code and your previous commit