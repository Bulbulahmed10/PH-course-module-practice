# Note::module-03 git practice in module-01

## Module-01 practice code & live link down below
## code link: https://github.com/Bulbulahmed10/ph-git-practice
## live link: https://bulbulahmed10.github.io/ph-git-practice/

01. What is Git ? What are the advantages of using Git?

**Answer 01::** Git is a DevOps(Development Operation) tool used for source code management. It is a free open-source version control system used to handle small to very large projects efficiently. Git is used to  tracking changes in the source code, enabling multiple developers to work together on non-linear development.

One of the biggest advantages of Git is its branching capabilities. Unlike centralized version control system, Git branches are cheap and easy to merge.This facilitates the feature branch workflow popular with many Git users. Feature branches provide an isolated environment for every changes to your codebase.

02. What do you understand by the term 'Version Control System'?

**Answer 02::** Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter.


03. What's the difference between Git and GitHub?

**Answer 03::** Git is a version control system that lets you manage and keep track of your source code history.

And GitHub is cloud-based hosting service that lets you manage Git repositories.


04. name a few Git commands with their function.

**Answer 04::**

# SETUP
## Configuring user information used across all local repositories

git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history

git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker

git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing


# SETUP & INIT
## Configuring user information, initializing and cloning repositories

git init
initialize an existing directory as a Git repository

git clone [url]
retrieve an entire repository from a hosted location via URL

# STAGE & SNAPSHOT
## Working with snapshots and the Git staging area
git status
show modified files in working directory, staged for your next commit

git add [file]
add a file as it looks now to your next commit (stage)

git reset [file]
unstage a file while retaining the changes in working directory

git diff
diff of what is changed but not staged

git diff --staged
diff of what is staged but not yet commited

git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot



05. Difference between git fetch and git pull.




