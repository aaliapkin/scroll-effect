## TODO:

- serialize trtansition
- animate shape on scroll
- add new shape to page 2
- remove filter by point numbers
- make bg transparent, keep only some solid backgrounds, f.e. hi my name bg keep
- make only rain move, since it can be moved infinitely
- make red dimmer
- save scroll on media change
- add contacts by shrink works
- add adaptive
- add fingeer manipulation
- figure out how to use fucking partials
- can scroll up down only in the middle of element, show it with cursor

## ideas

- interlacion
- Save this color #0d1014

## STUFF

### GIT STUFF

    git config --global alias.s status
    git config --global alias.l "log --oneline -n5"
    git config --global alias.ll "log -n2"
    git config --global alias.cm "!git add -A && git commit -m"
    git config --global alias.co checkout
    git config --global alias.cm "!git add '.' && git status && git commit"
    git config --global alias.cam "!git add '.' && git status && git commit --amend --no-edit"

    git config --global alias.wip "!git add '.' && git status && git commit -m 'WIP'"
    git config --global alias.rewip "!git cam"
    git config --global alias.unwip "!git log --oneline -n5 && git reset --mixed HEAD^ && git status"

    git config --global alias.posu "!git push origin --set-upstream "

    git config --global --unset alias.am
