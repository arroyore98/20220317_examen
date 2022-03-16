# 20220317_examen
```sh
####Comandos git

##Iniciar git
git init

##Adregar fichero a git
git add

##Para ver el estado
git status

##Para identificarnos
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

##Para cambiar editor por defecto
git config --global core.editor "vim"

##Para ver los cambios de la rama
git log 
git log --oneline

##Para hacer commit
git commit -m ""

##Para movernos entre comits
git checkout SHA-1-del-commit (entero o 5 cifras)

##Para cambiar el nombre
git branch -m historia

##Para crear una rama nueva y saltar a ella
git checkout -b 1900

##Para cambiar entre ramas
git checkout <rama>

##Para sacar el log de todo
git log --oneline --all

##Para sacar log de todo con grafo
git log --oneline --graph --all

##Comparar ramas
git diff <sha rama1> <sha rama2>

##fusionar rama (estando en una rama diferente):
git merge nombrerama

##Restaurar fichero (sin add):
git restore f1

##volver un paso atras un commit(con commit):
git reset --hard HEAD~1

##Arreglar un commit:
git commit --amend -m "textodelcommit"

##Cambiar nombre de rama:
git branch -M main
    
##Borrar rama:
git branch -d nombrerama
    
##Listar ramas:
git branch -l

##Rebase para borrar commits de la misma rama:
git rebase --interactive "hash"

##Merge para evitar conflicto:
git merge --no-ff --no-edit rama1

##Para ver diferencias entre commits: 
git diff hash commit1 hash commit2 

##Subir a GIT
echo "# 20221604_examen" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/arroyore98/20221604_examen.git
git push -u origin main
```
  
  ##ENLACES PROFE
  
  https://gist.github.com/repositorioinformatico/077b29bc25f8b48d492afd4d79cfac31
  https://gist.github.com/repositorioinformatico/6bca63d10f66ad6ee38e8320f1cbb70c
  https://gist.github.com/repositorioinformatico/cd7d99aef5ce9b4b642983cd1bc532d6
  https://gist.github.com/repositorioinformatico/34d48855c55e098b42a96728a7985fd2
  https://gist.github.com/repositorioinformatico/e13be768677dedc7e3cc6d48383e45c7
  https://gist.github.com/repositorioinformatico/0c17fb883ecdbce7fe767d014e7ca3a4
  https://gist.github.com/repositorioinformatico/cc2b0fbd413b5970dc73afba2e75cba2

  
