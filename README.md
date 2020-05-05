# GitCommandLine

## Create a new repo locally
new directory; `git init`

## Checkout a repo
Use online repo, first create on github.com ; `git clone` to local 

## Workflow local repo
Consists of three trees maintained by git.
1. Working directory ; holds the actual files
2. Index/stage ; `git add` to include the files
3. Head ; `git commit` (not in the remote repo yet!)

## Set up Javascript
`npm init` to intialize (set up node_modules packages ect.)
`npm install express --save` (to download and save a package which can be used)

## Gitignore files
.gitignore ; make sure that node_modules will not be uploaded

## Add & commit
`git status` to see which files have been modified or are developed new
`git add .` to add all the files to the stage
`git commit -m "commit message"` commit to the head including a message using -m "..."

## Pushing changes
`git push origin master` send the copy of the local work to the remote repo

## Branching
Branching used to develop features isloated from each other. Use other branches for development and merg the mback to the master upon completion
`git checkout -b feature_x` switch to new branch call feature_x
`git checkout master` to switch back to the master branch
`git branch -d feature_x` delete the branch

## Update & merge
`git pull` update local repo with newest commit