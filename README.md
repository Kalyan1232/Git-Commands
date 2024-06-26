#Git-Commands

1. Git commands are useful for Version control and Collaboration
2. It is a "DISTRIBUTED VERSION CONTROL SYSTEM"
3. VERSION CONTROL is of 3 types:
   3.1. Local Version Control -- maintains only a local copy only.
   3.2. Centralized Version Control System --maintains only a server copy only.
   3.3. Distributed Version Control System --maintains both local and server copy too.

HISTORY OF GIT:

4. Patches and Archieve files
5. Later used BitKeeper in 2002
6. Later Git was started in 2005

7. On Git we can run multiple programming languages.
8. Where Project was built is called as "WORKING DIRECTORY" and coming to Git, it works at "STAGING AREA".

NOTE: We need to specifically give the username and email id with the help of commands 
      -git config --global user.name "Your Name"
      -git config --global user.email "your.email@example.com"

LOCAL REPOSITORY

9. It can be achieved with the help of a command called "git init" (default branch is "MASTER" branch)
10. "git init" command creates a ".git" file in our working directory as a Hidden folder
11. To change the Branch of the git we use a command called "git init -b main"
12. "git status" command is to check the status of the git.
13. To move the updated code from Working directory to staging area we use the command called "git add filename".
14. To view all the git previous commits we use a command called "git log".
15. From staging area the file should be committed that can be done with the help of "git commit -m "TEXT MSG"".

NOTE: Git provides Integrity if any changes are required to made Git must and should know it that can be achieved with the help of CheckSum. The algorithm used was "SHA1".

16. Instead of adding into staging area and commiting it we can directly commit it with the help of "git commit -a -m "TEXT MSG"".

DIFF COMMAND:

-Finds the difference between Current Version vs Previous Version.
 
 command: git diff

To include all the files we use "git add."

For a file "U" - represents untracked
For a file "A" -represents Added

README.md where md represents MarkDown which makes document more beautiful.

NOTE: to remove the file from directory one way is to delete the file but another way is "git rm --cached filename".

