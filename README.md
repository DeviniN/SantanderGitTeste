# SantanderGitTeste
Aprendendo a utilizar o Git pelo curso do Santander
2024/06/11

## Oque é GIT?

Snapshots do estado do projeto
-git cmd
-git desktop
-git vscode

## Salvando Modificações no Git

* comando git push
* comando git pull
* comando git fetch
  
## Git status

-Untracked # arquivo adicionado no projeto
-Unmodified # salvo no estado atual (já recebeu commit e está salvo)
-Modified # sofreu ateração (não recebeu commit e não está salvo)
-Staged # sofreu ateração e foi para area de tranferencia "area do git add" (não recebeu commit e não está salvo)

## Comandos
-git clone http #clone repositorio
-git init #inicia o git
-git status # status do projeto # Git status
-git diff # o que foi modificado nos modificados
-git diff --staged #arquivos modificados no staged
-git commit -m "add new title"
-git log #lista ultimos commits
-git restore File #Retornar modificacoes no arquivo
-git restore --staged File #Retornar um arquivo do staged antes do commit
-git push
-git pull
-git fetch
-git diff origin/branch
-git branch new_name -git log --oneline --decorate
