# git101
Git tutorial

Other useful tutorials:
[https://try.github.io/](https://try.github.io/)
[https://www.atlassian.com/git/tutorials](https://www.atlassian.com/git/tutorials)
[https://www.tutorialspoint.com/git/index.htm](https://www.tutorialspoint.com/git/index.htm)

## Step 1 - install git
Install your git

Make sure it works
```bash
$ git
```

## Step 2 - configure git

[Tutorial](https://help.github.com/articles/setting-your-username-in-git/)

1. Open Terminal
2. Set your GitHub username and email
```
$ git config --global user.name "rusucosmin" #change this to yours
$ git config --global user.email "your-email@example.com"
```
3. Confirm that you have set the Git username and email correctly:
```
git config --global user.name
git config --global user.email
```

## Step 3 - clone the project

```
$ git clone https://github.com/dutylabs/git101
```

## Step 4 - create a new branch

```
git checkout -b new-feature-branch
```

## Step 5 - add yourself to the graduates

Open and modify index.html (add your name there).

## Step 6 - add, commit and push your changes

```
# add all your changes
$ git add -A
# commit the changes
$ git commit -m "Added myself to the index.html page"
# get the latest changes from master
$ git pull origin master
# Push your changes
$ git push -u origin new-feature-branch
```

## Step 7 - create a pull request

Open https://github.com/dutylabs/git101 in your browser
Your new branch should pop up at above the repo files
Click `New pull request`


## Step 8 - Wait for Review on the Pull Request

After creating the pull request, ping someone from the team to review it and merge.

## Step 9 - Go back to master

After the PR has been merged, it's time to go back to master.

```
# First, change to master
$ git checkout master
# Then, grab the latest changes from the repository
$ git pull origin master
# when you need to create another feature, go back to step 1.
```
