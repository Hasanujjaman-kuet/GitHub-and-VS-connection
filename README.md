# GitHub-and-VS-connection
git version 2.37.0.windows.1
PS E:\GitHub, ML & DS\GitHub\python> git config --global user.email "hasan.kuet18@gmail.com"
PS E:\GitHub, ML & DS\GitHub\python> git add New_program.py
PS E:\GitHub, ML & DS\GitHub\python>  git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   New_program.py

PS E:\GitHub, ML & DS\GitHub\python> git commit -m "add a python file" (for save)
[main 8dc6cd0] add a python file  
 1 file changed, 1 insertion(+)   
PS E:\GitHub, ML & DS\GitHub\python> git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 163.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Hasanujjaman-kuet/python.git
   f3c756b..8dc6cd0  main -> main
PS E:\GitHub, ML & DS\GitHub\python> git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 687 bytes | 40.00 KiB/s, done.
From https://github.com/Hasanujjaman-kuet/python
   8dc6cd0..90bf1f1  main       -> origin/main
Updating 8dc6cd0..90bf1f1
Fast-forward
 New_program.py | 1 +
 1 file changed, 1 insertion(+)
PS E:\GitHub, ML & DS\GitHub\python>

(If we press . [dot] at the place of git repositories, it automatically goes to browser VS code studio)
cls for all clean.
Up and Down arrows are used for “ next or previous comments”. Although comments all are cleaned.
