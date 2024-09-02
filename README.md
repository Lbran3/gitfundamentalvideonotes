# gitfundamentalvideonotes
-widely known version control system
Git = version control system (VCS); distributed to be exact; saving files or versions throughout the stages in life of a project; can retrieve past versions at any time; like a "time machine"

3 Types of Control Systems

local (VCS) = lightweight
            = all changes being made and stored locally on computer
            = individualized not collborative

centralized (VCS) = a single copy of project on a server and team members can make changes the copy

distributed = version Git uses
            = the complete project, all its history and metadata is copied to every developers own hard drive as a copy
            = used in collaboration platforms like: github. gitlab, and bitbucket.

version differences = referred as delta and diffs

git snapshots = every time you save or commit to a project, you are creating a snapshot of all files, history, and metadata for a project at a specific time

implicit = something done for you by other code behind the scenes
explicit = the approach to accomplishing the change you wish to have done by writing out clear instructions to be done

Different Statuses of Files

tracked = files that were in the last Git snapshot of the project
        = once tracked, file resides in 1 of 3 different statuses: Unmodified, Modified, and Staged 
  unmodified (local history) = you are tracking file, but file doesn't have any unsaved changes since it was last saved 
    in Git snapshot
  modified (working directory) = have made changes to the file but haven't yet saved them to the Git project
  staged (index/staging area)= making sure that the changes look good and what will be saved or committed in the next 
  Git snapshot
  untracked = when you decide you no longer want Git to track a file
Git basics

git init = creates a new .git repo and begins tracking
git add = moves modified files into the staging area
git status = shows you the status of your files
git commit = creates a snapshot and commit to Git
git config = set and read specific Git configs
git diff = shows changes between your working directory and staging area

Git Branches

git branch = list, create or delete branches
gut checkout = switch between branches
git merge = brings changes from one branch into another

Remote Repositories

git clone = copies entire repo into new local .git directory
git remote = creates and shows linked repos
git push = sends updates to associate repos
git pull =retrieves and integrates changes from other repos
git fetch = retrieves but doesn't integrate changes from other repos

Undoing Changes

git revert = creates a new commit that undoes a previous commit
git reset = removes files from the staging area
