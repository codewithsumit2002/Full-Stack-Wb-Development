This is a readme file
Git Detup:-
PS C:\Users\Sumit\Full Stack Web Development> git init
Initialized empty Git repository in C:/Users/Sumit/Full Stack Web Development/.git/
PS C:\Users\Sumit\Full Stack Web Development> git remote add origin https://github.com/codewithsumit2002/Full-Stack-Wb-Development.git
PS C:\Users\Sumit\Full Stack Web Development> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Sumit\Full Stack Web Development> git add .
PS C:\Users\Sumit\Full Stack Web Development> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.txt

PS C:\Users\Sumit\Full Stack Web Development> git commit -m "changes"
[master (root-commit) 88a4e0f] changes
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt
PS C:\Users\Sumit\Full Stack Web Development> git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 239 bytes | 9.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/codewithsumit2002/Full-Stack-Wb-Development.git
 * [new branch]      master -> master
PS C:\Users\Sumit\Full Stack Web Development>