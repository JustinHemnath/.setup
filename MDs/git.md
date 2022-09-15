#### Create an empty repository in github first, copy the url

#### Initialize in repo
    git init

#### Add changed files in directory to staging 
    (for all in current directory)     git add .
    (for a specific directory)         git add <directory name>

#### Commit changes to push
    git commit -m <commit message in quotes>

#### Add repo from github using 'remote'. Push using url of the repo in github and provide a nickname for it for future pushes
    git remote add <ref name> <url of repo in github>

#### Push using ref name
    git push <ref name> (For first time push, create a new main branch by adding 'main' at the end of the command above, else no need)