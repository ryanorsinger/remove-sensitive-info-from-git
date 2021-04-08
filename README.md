# Example Removing Sensitive Info From Git

## Contents of this repo:
- `credentials.txt` is a file containing sensitive information accidentally commited to git's history. 
- `script.py` represents the source code for a program we need to run.
- `README.md`
- `LICENSE` file

## What is this?
- This repository exists an example to demonstrate removing files with sensitive information from git's history
- We will be removing all references to a file from all of git's history

## So what?
- If you commit files with sensitive information like passwords to a permanent record machine, like git, you're going to have a bad time.
- Deleting the file isn't enough. The history of changes to that file are still accessible.
- As far as a git is concerned, deleting a file with sensitive information is only a new fact about the history of state changes to that file.


## Resources
- [GitHub's documentation](https://docs.github.com/en/github/authenticating-to-github/removing-sensitive-data-from-a-repository) on removing files from git history.
- Video tutorial to walk through the process of removing files with sensitive info from git's history
