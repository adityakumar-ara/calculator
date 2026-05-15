
Yeh aapke project folder me ek hidden .git folder bana dega, jisse Git wahan activate ho jayega.
command :- git init
_______________________________________________________________________
Check git status 
Command :- git status
-----------------------------------------------
Check branch name
Command :- git branch 
---------------------------------------------------
set new branch name if need 
Command :- git branch -M new branch name 
-------------------------------------

add sapecific file 
command :-  git add (file name )
-----------------------------------------------------------
add all files 
Command :- git add .
---------------------------------------
Apne GitHub repository ko link karein:
Command :- git remote add origin <URL>
_________________________________________________________________________________

Changes ko Save karna (Commit)
Command :- git commit -m "massage about changes"

_______________________________________________________________________________

Nayi branch banane aur usme shift hone ke liye:
Command :- git checkout -b branch-name 

-------------------------------------------------------

If create new repo.=> Pehle apne local Git ko GitHub repository se connect karein:
Command :- git remote add origin <GitHub_Repo_URL>

Phir code ko push kar dein:
Command :- git push -u origin main
                👆 YA 👇
Command :- git push -f origin main