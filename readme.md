**Git/Github course**

- Configurar/saber tu usuario o email

git config --global user.name "Sergio Ventura"
git config --global user.email "sergiovforesto"

- Si quieres comprobar tu configuración, puedes usar el comando:
  git config --list para mostrar todas las propiedades que Git ha configurado:

git config --list
user.name=John Doe
user.email=johndoe@example.com
color.status=auto
color.branch=auto
color.interactive=auto
color.diff=auto

- Comandos basicos git

*repo*  -> repository

*clone* -> traiga un repositorio desde Internet (repositorio remoto como Github) a su máquina local

*add* -> rastrear tus archivos y cambios con Git

*commit* -> guarda tus cambios en Git

*push* -> empujar sus cambios a su repositorio remoto en Github (u otro sitio web)

*pull* -> tirar de los cambios desde el repositorio remoto a su máquina local

*status* -> verifique qué archivos se están rastreando o deben confirmarse(commit)

*init* -> use este comando dentro de su proyecto para convertirlo en un repositorio de Git y comience a usar Git con esa base de código

1- git config –global user.name “[name]” ->sets author name
2- git config –global user.email “[email address]” ->sets author email id

3- git init [repository name] ->start new repository

4- git clone [url] ->obtain a repository from an existing URL.

5- git add [file] ->adds a file to the staging area.

6- git commit -m “[ Type in the commit message]” ->records or snapshots the file permanently in the version history.
7- git commit -a ->commits any files you’ve changed since then.&commits any files you’ve added

8- git diff ->shows the file differences which are not yet staged.
8.1- git diff –staged ->differences between the files in the staging area and the latest version present.
git diff [first branch] [second branch] ->differences between the two branches mentioned.

9- git reset [file] ->unstages the file, but it preserves the file contents.
10- git reset [commit] ->undoes all the commits after the specified commit and preserves the changes locally.
11- git reset –hard [commit] ->discards all history and goes back to the specified commit.

12 git status ->command lists all the files that have to be committed.

13- git rm [file] ->deletes the file from your working directory and stages the deletion.

14- git log ->used to list the version history for the current branch.
15- git log –follow[file] ->lists version history for a file, including the renaming of files also.

16- git show [commit] ->shows the metadata and content changes of the specified commit.

17- git tag [commitID] ->used to give tags to the specified commit.

18- git branch ->lists all the local branches in the current repository.
19- git branch [branch name] -> creates a new branch.
20- git branch -d [branch name] -> deletes the feature branch.

21- git checkout [branch name] -> used to switch from one branch to another
22- git checkout -b [branch name] ->creates a new branch and also switches to it.

23- git merge [branch name] ->merges the specified branch’s history into the current branch.

24- git remote add [variable name] [Remote Server Link] ->used to connect your local repository to the remote server.

25- git push [variable name] master ->sends the committed changes of master branch to your remote repository.
26- git push [variable name] [branch] ->sends the branch commits to your remote repository.
27- git push –all [variable name] ->pushes all branches to your remote repository.
28- git push [variable name] :[branch name] ->deletes a branch on your remote repository.

29- git pull [Repository Link] ->fetches and merges changes on the remote server to your working directory.

30- git stash save ->stores all the modified tracked files.

31- git stash pop ->restores the most recently stashed files.
32- git stash list ->lists all stashed changesets.
33- git stash drop ->discards the most recently stashed changeset.