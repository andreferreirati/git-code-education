MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ vim README.md
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git add README.md 
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   README.md

MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git commit -m "Adicionando arquivo README"
[master 454b610] Adicionando arquivo README
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git pull
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 4 (delta 1), reused 3 (delta 1)
Unpacking objects: 100% (4/4), done.
From https://github.com/andreferreirati/git-code-education
   a392e33..4a28da0  master     -> origin/master
Already up-to-date!
Merge made by the 'recursive' strategy.
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ ls
README.md		arquivo.txt		funcionalidade1.txt	teste.php
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$ git push origin master
Counting objects: 7, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 467 bytes | 0 bytes/s, done.
Total 4 (delta 2), reused 0 (delta 0)
To https://github.com/andreferreirati/git-code-education.git
   4a28da0..d77cef9  master -> master
MacBook-Pro-de-Andre-Ferreira:git-code-education andreferreira$
