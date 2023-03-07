# aspirantes-mir-html-y-css
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git clone https://github.com/Miguect/aspirantes-mir-html-y-css.git
Cloning into 'aspirantes-mir-html-y-css'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git branch develop
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout develop
Switched to branch 'develop'
PS C:\Users\Migue y Chris\Desktop\Ejercicios> md ejercicio1-html-y-css


    Directorio: C:\Users\Migue y Chris\Desktop\Ejercicios


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----      6/03/2023  6:52 p. m.                ejercicio1-html-y-css


PS C:\Users\Migue y Chris\Desktop\Ejercicios> cd aspirantes-mir-html-y-css
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git init
Reinitialized existing Git repository in C:/Users/Migue y Chris/Desktop/Ejercicios/aspirantes-mir-html-y-css/.git/
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> cd..
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git branch
* develop
  main
  pruebas
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout main
Switched to branch 'main'
M       Ejercicio1/bonus
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout --
M       Ejercicio1/bonus
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git branch
  develop
* main
  pruebas
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout develop
Switched to branch 'develop'
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout --
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git status
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .ssh
        .ssh.pub
        Ejercicio1/.gitignore
        Ejercicio1/mision_s3/
        aspirantes-mir-html-y-css/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git checkout -- .
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git status
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .ssh
        .ssh.pub
        Ejercicio1/.gitignore
        Ejercicio1/mision_s3/
        aspirantes-mir-html-y-css/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Migue y Chris\Desktop\Ejercicios> git add .
warning: LF will be replaced by CRLF in .ssh.
The file will have its original line endings in your working directory
warning: adding embedded git repository: Ejercicio1/mision_s3
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint: 
hint:   git submodule add <url> Ejercicio1/mision_s3
hint: 
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint: 
hint:   git rm --cached Ejercicio1/mision_s3
hint: 
hint: See "git help submodule" for more information.
warning: adding embedded git repository: aspirantes-mir-html-y-css
PS C:\Users\Migue y Chris\Desktop\Ejercicios> cd aspirantes-mir-html-y-css
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git branch develop
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git branch
  develop
* main
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git checkout develop
Switched to branch 'develop'
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> md ejercicio1-html-y-css


    Directorio: C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----      6/03/2023  7:09 p. m.                ejercicio1-html-y-css


PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> cd ejercicio1-html-y-css
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git add .
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git commit -m "Agrega el esqueleto del segundo ejercicio"
[develop b2d2ab0] Agrega el esqueleto del segundo ejercicio
 1 file changed, 6 insertions(+)
 create mode 100644 ejercicio1-html-y-css/index.html
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git add .
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git add .
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git commit -m "Agrega el cuerpo html del segundo ejercicio"
[develop d3aa989] Agrega el cuerpo html del segundo ejercicio
 1 file changed, 20 insertions(+)
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git add .
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git commit -m "agrega estilos al segundo ejercicio"
[develop ca6efe3] agrega estilos al segundo ejercicio
 2 files changed, 5 insertions(+), 1 deletion(-)
 create mode 100644 ejercicio1-html-y-css/style.css
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git checkout main
Deletion of directory 'ejercicio1-html-y-css' failed. Should I try again? (y/n) n
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git merge develop
Updating 5bc7c7b..ca6efe3
Fast-forward
 ejercicio1-html-y-css/index.html | 27 +++++++++++++++++++++++++++
 ejercicio1-html-y-css/style.css  |  3 +++
 2 files changed, 30 insertions(+)
 create mode 100644 ejercicio1-html-y-css/index.html
 create mode 100644 ejercicio1-html-y-css/style.css
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css\ejercicio1-html-y-css> cd..
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git branch
  develop
* main
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git remote add origin https://github.com/Miguect/aspirantes-mir-html-y-css.git
error: remote origin already exists.
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git push -u origin main
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 2 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (13/13), 1.39 KiB | 83.00 KiB/s, done.
Total 13 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/Miguect/aspirantes-mir-html-y-css.git
   5bc7c7b..ca6efe3  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
PS C:\Users\Migue y Chris\Desktop\Ejercicios\aspirantes-mir-html-y-css> git branch -d develop
Deleted branch develop (was ca6efe3).
