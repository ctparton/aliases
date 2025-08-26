Command: git chop 
Purpose: Deletes all git branches 

git config --global alias.chop '!git branch | grep -v $(git rev-parse --abbrev-ref HEAD) | xargs git branch -D'

FZF 

^+R -> Find files 
