1. stuck in wrong branch after cloning (in main instead of master) ->

“git checkout” command and specify the name of the branch you want to switch to

2. track changed locally and remotely:
2a. create react app locally. npx create-react app [appName]
2b. git init -- track changes locally
2c. gh repo create -- and follow the promps
      choose 'push an existing local repo to GH'
      add a remote: default = origin

3. change remote URL.
git remote set-url git@github.com:Fil-good/Pics.git
check if all good: git remote -v
