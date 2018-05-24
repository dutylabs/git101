# git101
Git tutorial

## Step 1 - install git
Install and configure your git

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

Open and modify index.html (add your name there)

## Step 6 - add, commit and push your changes

```
$ git add -A
$ git commit -m "Added myself to the index.html page"
$ git push -u origin new-feature-branch
```

## Step 7 - create a pull request

Open https://github.com/dutylabs/git101 in your browser
Your new branch should pop up at above the repo files
Click `New pull request`

