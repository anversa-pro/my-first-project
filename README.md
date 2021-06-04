# my-first-project
Proyecto de prueba para iniciarme en GitHub

Para tener un repositorio sincronizado no usar a través del descarga de .zip
entrar al archivo click derecho, abrir con powershell

1. Para clonar en local usar el comando
	git clone https://..... 
2. Modifiar local ara probar como se sincroniza
3. Identificarse en git 
	git config --global user.name "anversa-pro"
	git config --global user.email "angelavergaras@gmail.com"
4. Subir cambios en la nube con los comandos:
	git add <el archivo a sincronizar>
	git commit -m "[INIT] - initial commit"
	git push

5. Para verificar estado git status

/////////////////Codigo en power sell//////////////////////////////
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project>
    git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git add README.md
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git commit -m "[INIT] - initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Angela@DESKTOP-I0RQ6O2.(none)')
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git config --global user.name "anversa-pro"
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git config --global user.email angelavergaras@gmail.com
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git commit -m "[INIT] - initial commit"
[main 6ac3873] [INIT] - initial commit
 1 file changed, 7 insertions(+)
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 497 bytes | 248.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/anversa-pro/my-first-project.git
   c145ead..6ac3873  main -> main
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git add README.md
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git commit -m "[INIT] - refreshing list"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git push
Everything up-to-date
PS>                                         ctos\my-first-project>
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git add README.md
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git commit -m "[INIT] - refreshing list"
[main bedeb54] [INIT] - refreshing list
 1 file changed, 11 insertions(+), 2 deletions(-)
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 627 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/anversa-pro/my-first-project.git
   6ac3873..bedeb54  main -> main
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Angela\Documents\Holberton\Proyectos\my-first-project>