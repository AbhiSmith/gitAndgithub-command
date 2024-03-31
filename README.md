# DEMO

`clone
add
commit
push
pull
`

## create a new repository on command Line

`echo "Hello " >> README.md`
`git init`
`git add README.md` or `git add .`
`git commit -m "first commit"`
`git remote add origin git@github.com:sdkjs/demo-repo.git`
`git push -u origin main`

## some basic Command

`git init`
`git add.`
`git commith -m "commit massege"`
`git remote add origin git@github.com:sdkjs/demo-repo.git`
`gti push`

`la` =>> show all hidden file like (.git)
`ls -la`

## Configuration Git

`git config --list`

`git config --global user.name "Your Name"`

`git config --global user.email "you@youraddress.com"`

`git config --global push.default matching`

`git config --global alias.co checkout`

`git init`

`git config --list`

## Clone & Status

`git clone <- some link ->`

`git status`

`See Hidden file => ls -alias`

`untracked (new file that git doesn't yet track)`

`modified` (changed)

`staged` (file is ready to be committed)

`unmodified `(unchanged)

`git add <file name or use . for all add file>`

`git commit -m "Some message"`

## Push Command

`git push origin main (push - upload repo content to remote repo)`

## ssh key generate

`ssh-keygen -t rsa -b 4096  -C "email@mail.com"`

`testkey`
testkey.pub

-[Upload on gitHub]

set SSH add GPG keys

see key `cat testkey.pub`

set `Title` and `key`

## Adding your SSH key to ssh-agent

## Github Workflow

## git Branching

`git branch`

`git checkout -b <name-branch>` create branch

`git checkout main` switch branch

`git push -u origin second-demo-branch `

## merge compare

`git diff main` check difference compare to main

`git merge main` merge in main

`git branch -d second-demo-branch` delete branch
