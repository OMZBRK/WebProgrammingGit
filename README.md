
# Practice Repository

This repository was created for Chapter 9 lab exercises.

## Author
Omar Braik

## Purpose
To practice shell commands, Git initialization, status checking, staging, and committing.

## Reflection
This line has been change as asked in the third exercise.

## Challenge Task
This line is for the challenge task.

## Reflection Questions

Write short answers to the following:

1. Why is version control better than keeping many copied files with different names?

It prevents a "naming nightmare" (like final_v2_REAL_FINAL.zip). Instead of manual duplication, it records exact, immutable snapshots of your entire project, saving storage and making it easy to undo mistakes.

2. Why is `git status` often called a radar, compass, or checkpoint command?

It acts as a "compass" or "radar" because it tells you your current location in the project. It shows which files are modified, staged, or untracked so you never lose your bearings before running other commands.

3. What is the purpose of the staging area?

It is a "preview" area where you purposefully select and group specific changes to be included in the next snapshot (commit).

4. What is the difference between an untracked file and a modified file?

Untracked: A new file that Git has never saved in its history before.

Modified: A file Git already knows about, but which has been changed since the last commit.

5. Why does Git need your name and email before committing?

This configuration "stamps" your identity onto every commit. It ensures accurate attribution, which is essential for collaboration and knowing who made specific changes in the project history.

6. What does `git init` actually create?

It creates a hidden folder named .git. This directory is the "engine" that stores all repository history, configuration, and references to commits.

7. Why is it useful to write meaningful commit messages?

They serve as notes to your future self and teammates explaining what changed and why. Without them, Git's "time-traveling" ability to find specific past versions becomes useless.

8. What did you find easiest in this chapter?

Using basic shell commands like ls and pwd to see files and locations is often the most intuitive part of the setup.

9. What did you find most confusing in this chapter?

Understanding the "Three States" (Working Directory vs. Staging Area vs. Repository) and how files move between them can be tricky at first.

10. How does VS Code make Git easier to use?

It provides a built-in terminal for commands and a Source Control panel that visually shows changes, making it easier to compare versions and manage files without leaving the editor.
