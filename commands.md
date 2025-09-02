1. stuck in wrong branch after cloning (in main instead of master) ->

“$ git checkout” command and specify the name of the branch you want to switch to

2. track changed locally and remotely:
2a. $ create react app locally. npx create-react app [appName]
2b. $ git init -- track changes locally
2c. $ gh repo create -- and follow the promps
      choose 'push an existing local repo to GH'
      add a remote: default = origin

3. change remote URL.
$ git remote set-url git@github.com:Fil-good/Pics.git
check if all good: git remote -v

4. combine git add && git commit
4a. $ git config --global alias.add-commit '!git add -A && git commit'
4b. git add-commit -m 'My commit message'

5. clone a repo into local
5a. $ gh repo clone <repo name> -- or 5b.
5b. $ gh repo clone <URL repo>

6. get remote latest code
see https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository
6a. fetch
$ git fetch REMOTE-NAME
6b. merge (compare local changes with remote changes)
6c. pull = combination of fetch and merge


General commands:
7. rm -rf books -- recursive and force, to delete a directory
