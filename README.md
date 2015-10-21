# GitHub Tutorial

_by Derek Conde Barranco_

---
## Git vs. GitHub
###Git
* `Git` is version control by keeping **"snapshots"** of code
   * Runs in the command line but doesn't require github. 
   * View past commits(snapshots) to refer back to the original code that you've created
   * Use commits to go back to a version of your code in case anything goes wrong or if there's a groundbreaking mistake

###Github
* `Github` stores your code in the cloud(**internet**) and is used to check changes from Git.
    * `Github` is also used to collab with others on the same files.
    * Can be used to interact with code and snapshots from Git.
    * Runs in the command line
     * Uses git to interact with code from the snapshots  
     * Once you use git,it becomes a repository
---   
### Initial Setup
1. To first start setting up your `github`, you mush create an account on [github.com](http://www.github.com)
   * _Requires an email and password in order to sign up._
   * _You also need to create a username for your_ `github`
2. Make sure that have already setup your local machine with an IDE (**ex:nitrous and cloud 9**)
3. Inside of your IDE on your local machine, tell `git` to `git config --global username` "**Insert your username here**"
  * _You need this in order for your commits to be labeled correctly_   
4. Then tell `Git` your email address that will be used with your Git commits by `git config --global user.email` "**Insert your email address**"   
  * _make sure that it's the same email that you use in `Github`._
5. If you're setting up `github` with an ssh key, find your SSH key in your c9 IDE by going into the dashboard and opening up settings
6. You then go to ssh-keys and copy the correct key to Github to add it in.
7. The last step to confirm your IDE to `github` is to do `ssh -T git@github.com` and you're all set!

---
## Repository Setup
1. To set up a repo in cloud 9, make sure you added your directory to it by `Mkdir filename`  
2. Then you go to your `github`

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