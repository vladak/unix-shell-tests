# unix-shell-tests
Automated run of unix shell tests

Workflow:
  1. create new branch: `git branch -m branch_name`
  1. copy code to the branch, add the files: `git add .`
  1. make sure the code builds via `make` and produces a binary called `mysh`
  1. commit the files and push the new branch
  1. observe the result in [Github actions](https://github.com/vladak/unix-shell-tests/actions)
