1. powershell pwd
2. cd C:\Users\ZUL19\OneDrive\Escritorio
mkdir ejercicios
3. cd ejercicios
4. code .
5 Ejercicio 1 
6. Ejercicio 1 > README.txt
7. git config --global user.name Orel     
    git config --global user.email somosnoajidas18@gmail.com
8. git init 
Initialized empty Git repository in C:/Users/ZUL19/OneDrive/Escritorio/ejercicios/.git/
9.  git add .
    git commit -m "version inicial"


CÓDIGO DE GIT: 

ZUL19@LAPTOP-L0H92738 MINGW64 /
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=somosnoajidas18@gmail.com
user.name=OrelMeiri
user.name=Orel
user.name=Orel
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true

ZUL19@LAPTOP-L0H92738 MINGW64 /




CÓDIGO DE LA TERMINAL
PS C:\Users\ZUL19> pwd

Path
----
C:\Users\ZUL19


PS C:\Users\ZUL19> cd C:\Users\ZUL19\OneDrive\Escritorio
PS C:\Users\ZUL19\OneDrive\Escritorio> mkdir ejercicios


    Directorio: C:\Users\ZUL19\OneDrive\Escritorio


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/8/2023  10:39 AM                ejercicios


PS C:\Users\ZUL19\OneDrive\Escritorio> cd .\ejercicios\
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> code .
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> code .
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git init
Initialized empty Git repository in C:/Users/ZUL19/OneDrive/Escritorio/ejercicios/.git/
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git add .
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git commit -m "version inicial"
[master (root-commit) 8b54c6c] version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Ejercicio 1/README.md
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git commit -m "agrega solución primer ejercicio"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Ejercicio 1/README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git add .
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Ejercicio 1/README.md

PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git commit -m "agrega solución primer ejercicio"
[master 9f8522c] agrega solución primer ejercicio
 1 file changed, 9 insertions(+)
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\ZUL19\OneDrive\Escritorio\ejercicios>
