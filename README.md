## CONFIGURAÇÕES DO GIT
```bash
git config --global core.editor "code --wait"

git config --global --edit

git config --list

git config --system

git config --global

git config --local
```
## ARQUIVO DE CONFIGURAÇÃO SUGERIDO
```
[user]
    name = 
    email = 

[push]
    foolowTags = true
[core]
    editor = code --wait

[alias]
    s = !git status -s
    c = !git add --all && git commit -m
    l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
```
