# Basic Github Commands

* [Start a project](#start-a-project)
* [Commit changes](#commit-changes)
* [Push to remote repository](#push-to-remote-repository)
* [Pull from remote repository](#pull-from-remote-repository)
* [Check Status](#check-status)
* [Branching](#Branching)
* [Merging](#merging)

## Start a project

Initialize a local Git repository

```bash
git init
```

or

Create a local copy of a remote repository

```bash
git clone ssh://git@github.com/[username]/[repository-name].git
```

***

## Commit changes

Add all new and changed files to the staging area

```bash
git add *
```

Commit changes

```bash
git commit -m "Commit message"
```

## Push to remote repository

Push changes to remote repository

```bash
git push
```

## Pull from remote repository

Pull newest version of remote repository

```bash
git pull
```

## Check status

Check status

```bash
git status
```

***

## Branching

Create new branch `development`

```bash
git branch development
```

Switch to new branch

```bash
git checkout development
```

***

## Merging

Switch to Brach you want to merge in

```bash
git checkout main
```

Merge into `main` branch

```bash
git merge development
```
