# Gym-Git-Exercise-Solutions

BUNDLE 1
EXERCISE 1
````
```bash

3D@DESKTOP-U0DIQ3C MINGW64 /
$ cd S:

3D@DESKTOP-U0DIQ3C MINGW64 /s
$ git init git-exercises
Initialized empty Git repository in S:/git-exercises/.git/

3D@DESKTOP-U0DIQ3C MINGW64 /s
$ cd git-exercises

3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ code ,

3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ touch index.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ git commit -m "add readme.md"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ git add readme.md
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ git add index.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (master)
$ git branch -m master main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch --set-upstream-to=origin main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git commit
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch dev
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git checkout dev
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (dev)
$ git branch test
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (dev)
$ git branch -D test
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (dev)
$ git branch

````
Exercise 2
````
```bash


3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (dev)
$ git checkout main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git add home.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git add about.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git add team.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash pop@{1}
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash list
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git commit -m "Update project files"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git push origin main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git stash pop@{2}
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git reset --hard
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git status
````
BUNDLE 2
Exercise 1
````
```bash


3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch ft/bundle-2
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git switch ft/bundle-2
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git touch service.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git commit -m "Add services page"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git add README.md

3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git add service.html

3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git commit -m "Add services page"

3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git push origin ft/bundle-2
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git add .
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git commit -m "Fix review comments"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2


EXERCISE 2 
````
```bash


3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/bundle-2)
$ git switch main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git pull origin main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch ft/service-redesign
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git add services.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git commit -m "Update services.html with more services"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git push


````
BUNDLE 3
EXERCISE 1
````
```bash
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch ft/team-page
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git switch ft/team-page
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/team-page)
$ touch team.html
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/team-page)
$ git commit -m "update the team page"
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/team-page)
$ git push origin ft/team-page
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (ft/team-page)
$ git switch main
3D@DESKTOP-U0DIQ3C MINGW64 /s/git-exercises (main)
$ git branch ft/contact-page













