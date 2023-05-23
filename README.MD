
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



