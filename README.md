# This is my local Repo
PS C:\Users\mange\Desktop\DemoGitHub\localRepo>git branch -M main
PS C:\Users\mange\Desktop\DemoGitHub\localRepo>git branch
* main
PS C:\Users\mange\Desktop\DemoGitHub\localRepo>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Mangeshlawande/LocalRepo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\mange\Desktop\DemoGitHub\localRepo>git add .                                        
PS C:\Users\mange\Desktop\DemoGitHub\localRepo>git commit -m "create new paragraph"             
[main 014e746] create new paragraph
 1 file changed, 32 insertions(+)
CLEAR
=============================
git remote add origin <link>
git remote -v =>to verify origin
git branch (to check branch)
git branch -M main 

git push -u origin main
-u for get upstream 