# Week 3 Terminal Log

This file records the terminal commands used during the Week 3 assignment.

## Repository setup and navigation

| Command | What it does |
|---|---|
| `cd ~/-iyf-s12-week-03-Jean-ugine` | Navigates to the Week 3 repository. |
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and folders in the current directory. |
| `ls ~` | Lists items in the home directory. |
| `ls -d ~/iyf-s12-week-02*` | Finds the Week 2 repository folder. |

## Copying portfolio files

| Command | What it does |
|---|---|
| `cp ~/iyf-s12-week-02-Jean-ugine/{index.html,about.html,projects.html,contact.html,styles.css} .` | Copies the portfolio pages and stylesheet into Week 3. |
| `cp ~/iyf-s12-week-02-Jean-ugine/*.jpg .` | Copies JPG images into Week 3. |
| `ls *.jpg` | Lists JPG images in the current directory. |
| `find ~/iyf-s12-week-02-Jean-ugine -type f \| grep -Ei '\.(jpg\|jpeg\|png\|webp)$'` | Finds image files in the Week 2 repository. |
| `grep -nEi 'img\|src=' *.html` | Searches HTML files for image references. |

## Git commands

| Command | What it does |
|---|---|
| `git status --short` | Shows changed and untracked files. |
| `git add index.html about.html projects.html contact.html styles.css *.jpg` | Stages portfolio files and images. |
| `git commit -m "Add: Week 2 portfolio as the starting point"` | Creates the required starting commit. |
| `git push -u origin main` | Pushes the main branch to GitHub and sets its upstream. |

## Creating documentation

| Command | What it does |
|---|---|
| `touch terminal-log.md` | Creates the terminal log file. |
| `code terminal-log.md` | Opens the file in Visual Studio Code. |

## Git Merge Conflict Exercise

- Created two branches from `main`: `feature/conflict-a` and `feature/conflict-b`.
- Added `conflict-practice.txt` independently on both branches with different content.
- Merged `feature/conflict-a` into `main`.
- Merging `feature/conflict-b` caused an add/add merge conflict.
- Resolved the conflict by keeping both messages in `conflict-practice.txt`.
- Staged the resolved file and completed the merge with commit `bb68276`.
- Pushed the completed merge to GitHub.

This exercise helped me practise creating branches, merging changes, identifying conflicts, resolving conflicts, and completing a merge.