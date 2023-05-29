
Arbusta@N-407 MINGW64 ~/Desktop
$ mkdir "Ejercicio_final_GIT_HUB"

Arbusta@N-407 MINGW64 ~/Desktop
$ cd "Ejercicio_final_GIT_HUB"

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB
$ ls

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB
$ git clone https://github.com/Matias-lab-ARB/Devjumpers.git
Cloning into 'Devjumpers'...
warning: You appear to have cloned an empty repository.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB
$ cd Devjumpers


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ touch README.MD


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.MD

nothing added to commit but untracked files present (use "git add" to track)


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.MD


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git commit -m "Se crea repositorio y se crea el archivo README y COMMIT inicial"
[main (root-commit) e8ad71d] Se crea repositorio y se crea el archivo README y COMMIT inicial
 1 file changed, 22 insertions(+)
 create mode 100644 README.MD

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 505 bytes | 505.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Matias-lab-ARB/Devjumpers.git
 * [new branch]      main -> main


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ touch privado.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ mkdir privada

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add privada

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.MD
        new file:   privado.txt


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git commit -m "Se agrega carpeta privada y archivo privado.txt"
[main 60b2353] Se agrega carpeta privada y archivo privado.txt
 2 files changed, 1 insertion(+)
 create mode 100644 privado.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 362 bytes | 362.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Matias-lab-ARB/Devjumpers.git
   15b7d8f..60b2353  main -> main

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ ls
README.MD  privada/  privado.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add privada

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ touch .gitignore

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ commit -m "Se crea el archivo para ignorar las carpetas y el archivo"
bash: commit: command not found

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Everything up-to-date

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git commit -m "Se crea el archivo para ignorar las carpetas y el archivo"
[main be8f3e8] Se crea el archivo para ignorar las carpetas y el archivo
 1 file changed, 2 insertions(+)
 create mode 100644 .gitignore

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 380 bytes | 380.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Matias-lab-ARB/Devjumpers.git
   60b2353..be8f3e8  main -> main

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ touch 1.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git checkout -b v0.2
Switched to a new branch 'v0.2'

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ touch 2.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git commit -m "Se crea la rama y los archivos 1 y 2"
[v0.2 a054319] Se crea la rama y los archivos 1 y 2
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git push -u origin v0.2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 354 bytes | 354.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'v0.2' on GitHub by visiting:
remote:      https://github.com/Matias-lab-ARB/Devjumpers/pull/new/v0.2
remote:
To https://github.com/Matias-lab-ARB/Devjumpers.git
 * [new branch]      v0.2 -> v0.2
branch 'v0.2' set up to track 'origin/v0.2'.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git merge v0.2
Updating be8f3e8..a054319
Fast-forward
 1.txt | 0
 2.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Matias-lab-ARB/Devjumpers.git
   be8f3e8..a054319  main -> main

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git commit -m "Se pone texto en el arhivo 1.txt"
[main afd66dd] Se pone texto en el arhivo 1.txt
 1 file changed, 1 insertion(+)

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git checkout v0.2
Switched to branch 'v0.2'
Your branch is up to date with 'origin/v0.2'.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git commit -m "Se pone texto ADIOS en el archivo 1.txt"
[v0.2 9a31075] Se pone texto ADIOS en el archivo 1.txt
 1 file changed, 1 insertion(+)

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git merge v0.2
Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main|MERGING
$ git branch -- merge

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main|MERGING
$ git branch --merge
* main
  merge

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main|MERGING
$ git branch --no-merge
  v0.2

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main|MERGING
$ git add .

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main|MERGING
$ git commit -m "Conflictos resueltos"
[main c48566f] Conflictos resueltos

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git merge
Already up to date.

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 773 bytes | 773.00 KiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/Matias-lab-ARB/Devjumpers.git
   a054319..c48566f  main -> main

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git branch -D v0.2
Deleted branch v0.2 (was 9a31075).

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git config --global alias.list "log --decorate --oneline --graph --all"


Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$ git log --oneline --decorate --all --graph
*   c48566f (HEAD -> main, origin/main) Conflictos resueltos
|\
| * 9a31075 Se pone texto ADIOS en el archivo 1.txt
* | afd66dd (merge) Se pone texto en el arhivo 1.txt
|/
* a054319 (origin/v0.2) Se crea la rama y los archivos 1 y 2
* be8f3e8 Se crea el archivo para ignorar las carpetas y el archivo
* 60b2353 Se agrega carpeta privada y archivo privado.txt
* 15b7d8f Se modificó el archivo README
* e8ad71d Se crea repositorio y se crea el archivo README y COMMIT inicial

Arbusta@N-407 MINGW64 ~/Desktop/Ejercicio_final_GIT_HUB/Devjumpers (main)
$



